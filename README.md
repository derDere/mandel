# mandel
A mandelbrot set shaped code calculating and displaying the mandelbrot set.

Share, play, have fun. ;D

## Usage
Enter the following command:

```sh
cat > mandel.c
```

Then enter the source code:

```c
                                                     /*
                                                  *****/
                                                   double
                                                  fabs /*
                                          */  (); double s =
                                           100.0, u = 4.0 / 100.0;
                                       char c ( double xp, double
                                       yp ) { double x= -2.0 + (xp
                            *         ( u / 2.0) ), y = -2.0 + (yp *
                        u ) , a     = x, b = y, n = 30.0; while ( n
                      < 300.0 ) {   double aa = ( a * a ) - ( b * b
                      ) , bb = 2.0 * a * b; a = aa + x ; b = bb+y;/*
..................*/if ( fabs (a + b) > 200.0 ) { return ' '; }
                      n++ ; } return '#'; } main ( ) { double x, y;
                       for ( y = 23.0 ; y < s - 23.0; y++ ) { for (
                       x = 0.0 ;   x < ( s + s ) - 80 ; x++ ) {/**/
                           /**/      printf ( "%c", c ( x, y ) ) ; }
                                       printf ( "\n" ) ; } } /* $$ %
                                       .( //%§§&/)%/"!"!§"§$()%$%§"
                                         --''###*&"""()////$%§§$$'
                                          _####**++++P.A.D.'#'''##
                                               '''1992###''''
                                                    ##*
                                                   ~###'
                                                   '"|"'
                                                     */
```

Exit using Ctrl+C

Then compile using the following command:

```sh
gcc -o mandel mandel.c
```

And finaly run it using:

```sh
./mandel
```

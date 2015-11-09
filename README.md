# Car-Profile
SighSeeing focus test car profile, based on Car-test.brf

As car route are usually longer than bicycle routes, you may notice time outs in Locus fo routes longer than 50-100 km, if navigation is configured to use Brouter. The reason is Brouter is computation intensive and Locus may not be patient enough.

There are 2 solutions>

- Generate GPX file and navigate along it.

- Generate GPX file, but then choose Server mode option, with assigning to Brouter navigation mode (Car fast/short).
It makes Brouter to use just analysed data for the same future destination+profile calculations, So if you use the same destination+profile later in Locus, it will be fast enough to fit the time out limits. The data are volatile, so one must not use other Brouter routing in between.


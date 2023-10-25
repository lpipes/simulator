# simulator
Usage: ./simulate_sequences.pl [total-fragments] [error-rate] [fragment-size]

Arguments:
  total-fragments             Specify the total number of fragments. This is a required argument and must be a positive integer.
  error-rate                  Specify the error rate desired [i.e.: if 1% is desired, use 0.01]. This is an optional argument and must be positive. The default is 0.01.
 fragment-size                Specify the fragment size (bp). This is an optional argument and has to be used with error-rate. The default is 150bp.

Example:
  ./simulate_sequences.pl 100 0.01 150

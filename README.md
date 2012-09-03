stockquote
==========

Ruby script to get the latest stock price for any stock symbol.  Uses the Google finance API.

Example Usage

sq = Stockquote.new
puts sq.price('GOOG')
puts sq.price('AAPL')
puts sq.price('AMZN')


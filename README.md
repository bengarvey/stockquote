stockquote
==========

Ruby script to get the latest stock price for any stock symbol.  Uses the Google finance API.

Example Usage

sq = Stockquote.new<br>
puts sq.price('GOOG')<br>
puts sq.price('AAPL')<br>
puts sq.price('AMZN')<br>


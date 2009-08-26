# Install
  rip install git://github.com/bmizerany/muni.git

# Setup
`muni` will growl you when you have at least 10 minutes
to catch the last bus before your desired leave time.
Select the routes until you see times [here](http://www.nextbus.com/predictor/adaRoute.jsp?a=sf-muni)

Here is the format for `~/.muni`:

  work: http://www.nextbus.com/predictor/adaPrediction.jsp?a=sf-muni&r=47&d=47_IB2&s=6766
  home: http://www.nextbus.com/predictor/adaPrediction.jsp?a=sf-muni&r=45&d=45_IB2&s=6769

# Use
I want to leave close to 50 minutes from now
  `$ muni work 50`
I want to leave home at the next bus
  `$ muni work`

remind - Quickly add events to your Google Calendar

Setup:
git clone https://github.com/andyforceno/remind/
cd to remind/
chmod +x remind
./remind

The first time you execute remind OAuth setup will run
Execute ./remind after setup finishes to start using remind

Usage: 
remind [OPTIONS] <text>

-a | add 	Add an event with specific start and end times (Not yet implemented)
-q | quick	Quickly add an event to your calendar
		<event text> at <time> on <day>
		"Get milk at 5pm on Wednesday"
		"Do something at 21:05"

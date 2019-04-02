# Detail of the settings
Most of the native settings have options that can be passed in the *optionscode* field to make them finest. These options follow the type and are separated with as newline character (\n).
## text
Nothing
## numeric
* min : the minimum value
* max : the maximum value
* step : the step of incrementation
*Example*
```
$setting = [
   'numeric' => [
      'title' => 'A numeric field',
      'description' => 'From 1 to 99 with step of 2',
      'optionscode' => "numeric\nmin=1\nmax=99\nstep=2",
      'value' => 1,
      'disporder' => 1
   ]
];
```
##textarea
Nothing
##yesno

##onoff

##select

##forumselect

##forumselectsingle

##groupselect

##groupselectsingle

##radio

##checkbox

##language

##adminlanguage

##cpstyle

#php

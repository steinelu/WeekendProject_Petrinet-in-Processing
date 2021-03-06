# -WeekendProject-Petrinetwork-in-Processing
A Petrinetwork "simulation" written in Processing, only fundamental functionality

normal mode:
- klick on transition to firing the transition. It only fires if all connected places pointing towards it have at least one mark. If no place points towards it, it generates a mark.
- type 'e' to enter edit mode

![normal mode sceenshot](https://github.com/steinelu/WeekendProject_Petrinet-in-Processing/blob/master/normal_mode_pn.PNG)

edit mode:
- transitions and places can now be dragged around with middle click.
- type 't' to create a new transition on current cursor position.
- type 'p' to create a new place on current cursor position.
- type 'x' over an transition or place to delete it.
- type 'e' to exit edit mode
- left click on a place to add one mark
- right click on a place to remove one mark
- left click and hold to create an new edge from current place/transition to another transition/place

![edit mode sceenshot](https://github.com/steinelu/WeekendProject_Petrinet-in-Processing/blob/master/edit_mode_pn.PNG)

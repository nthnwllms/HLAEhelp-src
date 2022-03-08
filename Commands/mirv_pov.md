*Turns a GOTV demo into a fake POV demo for the chosen player index.*

#### Usage

`mirv_pov <playerIndex>` // enter the playerIndex of the desired POV before loading the GOTV demo. To disable set to 0 (default).

To find the entity index number, load the demo and enter `mirv_listentities isPlayer=1` once the desired player has joined.
The index is the number in the first (left-most) column.

<img src="..\\\\images\\mirv_listentities_isPlayer1.png" alt="mirv_listentities isPlayer=1" class="autosize" />


<center>*mirv_fix forcePostDataUpdateChanged can also be used with this.*</center>

@alert tip
When using `mirv_pov` the `cl_show_observer_crosshair 0|1|2` engine command is supported. Set this variable to 2 to see the players crosshair as it was in the demo.
@end
User guide
==========

.. image:: /images/barclogo.png
    :width: 245px
    :height: 131px 
    :align: right  
    :alt: BARC logo 

Getting Started with BARC
^^^^^^^^^^^^^^^^^^^^^^^^^

The BARC tool is split into three distinct sections, the Annotation toolbox, the Lab book and the Report generator. 

**The Annotation toolbox**

The Annotation toolbox will allow the user to select from various icons and annotate or markup on the displayed meteorological data. It features specific weather/forecasting icons which the user can select and place on the active content. The toolbox hosts a variety of freeform drawing tools which enable the user to mark features such as strong temperature or moisture gradients with ease as well as highlight features that they wish to draw attention to. 

**The Lab book**

The lab book allows the user to input notes and comments which can be linked to the active content and to the users annotations and markup. Both the comments and the annotations can be saved to allow the user to revisit their previous work.

**The Report Generator**

The report generator provides the capability to generate case studies and model evaluation feedback reports. It features a comprehensive search and allows users to find previous reports and events from keywords and metadata.


Workspace  basics
^^^^^^^^^^^^^^^^^

When you open the BARC component it will appear on the right side of the browser. 


The main toolbar provides the basic tools the user requires to start using BARC.

.. image:: /images/full_toolbox.png
    :width: 383px
    :height: 51px
    :alt: Selection, navigation, drawing and type toolbar

The toolbar contains two distinct sets of tools. The first set (A) are used for navigation, e.g zoom and move. The second (B) are freeform drawing tools. When you hover over any of the buttons a tooltip will give an overview of the functionilty of that button. 

.. image:: /images/toolbox_breakdown.png
    :width: 383px    
    :height: 152px
    :alt: Selection, navigation, drawing and type toolbar

Selection and navigation tools
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: /images/undo.png
    :width: 26px
    :height: 30px
    :alt: Undo button
    :align: left

Undo

By using the undo tool you can easily undo multiple steps from your annotations.

.. image:: /images/redo.png
    :width: 26px  
    :height: 30px
    :align: left
    :alt: Redo button

Redo

By using the redo tool you can easily redo your last step.


.. image:: /images/zoomin.png
    :width: 26px    
    :height: 30px
    :alt: Zoom in button
    :align: left


Zoom in tool

By using this tool you can magnify the view by selecting the left mouse button.

.. image:: /images/zoomout.png
    :width: 26px    
    :height: 30px
    :alt: Zoom out button
    :align: left


Zoom out tool

This tool will reduce the the view of the image by left clicking the mouse.


.. image:: /images/move.png
    :width: 26px    
    :height: 30px
    :alt: Pan/move button
    :align: left

Move/pan tool

This tool will move/pan the map view by holding the left mouse button and dragging. This used in conjuction with the zoom tool allow the user to define their view.



.. image:: /images/boxzoom.png
    :width: 26px    
    :height: 30px
    :alt: Box selection zoom
    :align: left

Box zoom tool

The box zoom tool allows the user to define a rectangular region to zoom. This is done by holding down the left mouse button and dragging to the desired area.

.. image:: /images/wheelzoom.png
    :width: 26px    
    :height: 30px
    :alt: Mouse wheel zoom
    :align: left

Mouse wheel zoom tool

This tool has the same effect as the zoom in and zoom out buttons but is triggered by the user moving the mouse wheel fowards to zoom in and backwards for zooming out.


Drawing and type tools
^^^^^^^^^^^^^^^^^^^^^^


.. image:: /images/boxadd.png
    :width: 26px    
    :height: 30px
    :alt: Box add button
    :align: left


Box add tool

Use this tool to create a box to highlight features. To use this tool left click anywhere on the active content and then drag to a specfic point.

.. image:: /images/freehand.png
    :width: 26px    
    :height: 30px
    :alt: Freehand drawing tool
    :align: left

Freehand drawing tool

Allows the user to draw freehand on the displayed content. Line thickness and colour can be selected.

.. image:: /images/polyadd.png
    :width: 26px    
    :height: 30px
    :alt: Polygon add tool
    :align: left

Polygon add tool

Use this tool to create polygons on the displayed content. 

To add a point left click anywhere on the active content. 

To move a point tap and drag the exisiting point to a new location. 

To delete a point tap to select a point and then select the backspace key.

To move or delete multiple points at once:

Move selection
Select point(s) with SHIFT+tap, then drag anywhere on the plot. Selecting and then dragging a specific point will move both.

Delete selection
Select point(s) with SHIFT+tap, then press BACKSPACE while the mouse is within the plot area.


.. image:: /images/polyedit.png
    :width: 26px   
    :height: 30px
    :alt: Polygon edit tool
    :align: left

Polygon edit tool

Use this tool to edit exsisting polygons you have created. 

.. image:: /images/textadd.png
    :width: 26px    
    :height: 30px
    :alt: Text add tool
    :align: left

Text add tool.

Use this tool to added text to the active content. 

Meteorological symbols
^^^^^^^^^^^^^^^^^^^^^^

BARC has a host of specfic meteorological symbols availble. These symbols are displayed in groups of similar weather features or characteristics. To select a group of symbols use the dropdown toolbar to select the group and then select the specfic symbol you want to use. More information about what the symbol represents is displayed when you hover over the icons. Group 0 - 9 reference the well established WMO present weather symbols.


+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image::   /images/pw_symbols/pw-000.png | 0  |  Cloud development not observed or not   observable                                                                                                                                                                                                                          |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-001.png   | 1  |  Cloud generally dissolving or   becoming less developed                                                                                                                                                                                                                     |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-002.png   | 2  |  State of sky on the whole   unchanged                                                                                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-003.png   | 3  |  Clouds generally forming or   developing                                                                                                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-004.png   | 4  |  Visibility reduced by smoke, e.g.   veldt or forest fires, industrial smoke or volcanic ashes                                                                                                                                                                               |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-005.png   | 5  |  Haze                                                                                                                                                                                                                                                                        |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-006.png   | 6  |  Widespread dust in suspension in   the air, not raised by wind at or near the station at the time of   observation                                                                                                                                                          |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-007.png   | 7  |  Dust or sand raised by wind at or   near the station at the time of observation, but not well developed dust   whirl(s) or sand whirl(s), and no duststorm or sandstorm seen; or, in the   case of ships, blowing spray at the station                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-008.png   | 8  |  Well developed dust or sand   whirl(s) seen at or near the station during the preceding hour or at the time   of observation, but no dust storm or sandstorm                                                                                                                |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-009.png   | 9  |  Duststorm or sandstorm within   sight at the time of observation, or at the station during the preceding   hour                                                                                                                                                             |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-010.png   | 10 |  Mist                                                                                                                                                                                                                                                                        |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-011.png   | 11 |  Patches of shallow fog or ice fog   at the station, whether on land or sea not deeper than about 2 metres on land   or 10 metres at sea                                                                                                                                     |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-012.png   | 12 |  More or less continuous shallow   fog or ice fog at the station, whether on land or sea, not deeper than about   2m/land or 10m/sea                                                                                                                                         |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-013.png   | 13 |  Lightning visible, no thunder   heard                                                                                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-014.png   | 14 |  Precipitation within sight, not   reaching the ground or the surface of the sea                                                                                                                                                                                             |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-015.png   | 15 |  Precipitation within sight,   reaching the ground or the surface of the sea, but distant, i.e. > 5 km   from the station                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-016.png   | 16 |  Precipitation within sight,   reaching the ground or the surface of the sea, near to, but not at the   station                                                                                                                                                              |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-017.png   | 17 |  Thunderstorm, but no precipitation   at the time of observation                                                                                                                                                                                                             |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-018.png   | 18 |  Squalls at or within sight of the   station during the preceding hour or at the time of observation                                                                                                                                                                         |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-019.png   | 19 |  Funnel clouds at or within sight   of the station during the preceding hour or at the time of observation                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-020.png   | 20 |  Drizzle (not freezing) or snow   grains, not falling as showers, during the preceding hour but not at the time   of observation                                                                                                                                             |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-021.png   | 21 |  Rain (not freezing), not falling   as showers, during the preceding hour but not at the time of observation                                                                                                                                                                 |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-022.png   | 22 |  Snow, not falling as showers,   during the preceding hour but not at the time of observation                                                                                                                                                                                |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-023.png   | 23 |  Rain and snow or ice pellets, not   falling as showers; during the preceding hour but not at the time of   observation                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-024.png   | 24 |  Freezing drizzle or freezing rain;   during the preceding hour but not at the time of observation                                                                                                                                                                           |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-025.png   | 25 |  Shower(s) of rain during the   preceding hour but not at the time of observation                                                                                                                                                                                            |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-026.png   | 26 |  Shower(s) of snow, or of rain and   snow during the preceding hour but not at the time of observation                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-027.png   | 27 |  Shower(s) of hail, or of rain and   hail during the preceding hour but not at the time of observation                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-028.png   | 28 |  Fog or ice fog during the   preceding hour but not at the time of observation                                                                                                                                                                                               |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-029.png   | 29 |  Thunderstorm (with or without   precipitation) during the preceding hour but not at the time of   observation                                                                                                                                                               |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-030.png   | 30 |  Slight or moderate duststorm or   sandstorm, has decreased during the preceding hour                                                                                                                                                                                        |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-031.png   | 31 |  Slight or moderate duststorm or   sandstorm, no appreciable change during the preceding hour                                                                                                                                                                                |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-032.png   | 32 |  Slight or moderate duststorm or   sandstorm, has begun or has increased during the preceding hour                                                                                                                                                                           |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-033.png   | 33 |  Severe duststorm or sandstorm, has   decreased during the preceding hour                                                                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-034.png   | 34 |  Severe duststorm or sandstorm, no   appreciable change during the preceding hour                                                                                                                                                                                            |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-035.png   | 35 |  Severe duststorm or sandstorm, has   begun or has increased during the preceding hour                                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-036.png   | 36 |  Slight/moderate drifting snow,   generally low (below eye level)                                                                                                                                                                                                            |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-037.png   | 37 |  Heavy drifting snow, generally low   (below eye level)                                                                                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-038.png   | 38 |  Slight/moderate blowing snow,   generally high (above eye level)                                                                                                                                                                                                            |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-039.png   | 39 |  Heavy blowing snow, generally high   (above eye level)                                                                                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-040.png   | 40 |  Fog or ice fog at a a distance at   the time of observation, but not at station during the preceding hour, the   fog or ice fog extending to a level above that of  the observer                                                                                            |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-041.png   | 41 |  Fog or ice fog in patches                                                                                                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-042.png   | 42 |  Fog/ice fog, sky visible, has   become thinner during the preceding hour                                                                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-043.png   | 43 |  Fog/ice fog, sky invisible, has   become thinner during the preceding hour                                                                                                                                                                                                  |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-044.png   | 44 |  Fog or ice fog, sky visible, no   appreciable change during the past hour                                                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-045.png   | 45 |  Fog or ice fog, sky invisible, no   appreciable change during the preceding hour                                                                                                                                                                                            |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-046.png   | 46 |  Fog or ice fog, sky visible, has   begun or has become thicker during preceding hour                                                                                                                                                                                        |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-047.png   | 47 |  Fog or ice fog, sky invisible, has   begun or has become thicker during the preceding hour                                                                                                                                                                                  |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-048.png   | 48 |  Fog, depositing rime, sky   visible                                                                                                                                                                                                                                         |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-049.png   | 49 |  Fog, depositing rime, sky   invisible                                                                                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-050.png   | 50 |  Drizzle, not freezing,   intermittent, slight at time of ob.                                                                                                                                                                                                                |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 51 |  Drizzle, not freezing, continuous,   slight at time of ob.                                                                                                                                                                                                                  |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 52 |  Drizzle, not freezing,   intermittent, moderate at time of ob.                                                                                                                                                                                                              |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 53 |  Drizzle, not freezing, continuous,   moderate at time of ob.                                                                                                                                                                                                                |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 54 |  Drizzle, not freezing,   intermittent, heavy at time of ob.                                                                                                                                                                                                                 |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 55 |  Drizzle, not freezing, continuous,   heavy at time of ob.                                                                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 56 |  Drizzle, freezing, slight                                                                                                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 57 |  Drizzle, freezing, moderate or   heavy (dense)                                                                                                                                                                                                                              |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 58 |  Rain and drizzle, slight                                                                                                                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 59 |  Rain and drizzle, moderate or   heavy                                                                                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 60 |  Rain, not freezing, intermittent,   slight at time of ob.                                                                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 61 |  Rain, not freezing, continuous,   slight at time of ob.                                                                                                                                                                                                                     |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 62 |  Rain, not freezing, intermittent,   moderate at time of ob.                                                                                                                                                                                                                 |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 63 |  Rain, not freezing, continuous,   moderate at time of ob.                                                                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 64 |  Rain, not freezing, intermittent,   heavy at time of ob.                                                                                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 65 |  Rain, not freezing, continuous,   heavy at time of ob.                                                                                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 66 |  Rain, freezing, slight                                                                                                                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 67 |  Rain, freezing, moderate or   heavy                                                                                                                                                                                                                                         |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 68 |  Rain or drizzle and snow,   slight                                                                                                                                                                                                                                          |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 69 |  Rain or drizzle and snow, moderate   or heavy                                                                                                                                                                                                                               |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 70 |  Intermittent fall of snowflakes,   slight at time of ob.                                                                                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 71 |  Continuous fall of snowflakes,   slight at time of ob.                                                                                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 72 |  Intermittent fall of snowflakes,   moderate at time of ob.                                                                                                                                                                                                                  |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 73 |  Continuous fall of snowflakes,   moderate at time of ob.                                                                                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 74 |  Intermittent fall of snowflakes,   heavy at time of ob.                                                                                                                                                                                                                     |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 75 |  Continuous fall of snowflakes,   heavy at time of ob.                                                                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 76 |  Diamond dust (with or without   fog)                                                                                                                                                                                                                                        |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 77 |  Snow grains (with or without   fog)                                                                                                                                                                                                                                         |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 78 |  Isolated star, like snow crystals   (with or without fog)                                                                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 79 |  Ice pellets                                                                                                                                                                                                                                                                 |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 80 |  Rain shower(s), slight                                                                                                                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 81 |  Rain shower(s), moderate or   heavy                                                                                                                                                                                                                                         |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 82 |  Rain shower(s), violent                                                                                                                                                                                                                                                     |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 83 |  Shower(s) of rain and snow,   slight                                                                                                                                                                                                                                        |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 84 |  Shower(s) of rain and snow,   moderate or heavy                                                                                                                                                                                                                             |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 85 |  Snow shower(s), slight                                                                                                                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 86 |  Snow shower(s), moderate or   heavy                                                                                                                                                                                                                                         |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 87 |  Shower(s) of snow pellets or small   hail, with or without rain or rain and snow mixed, slight                                                                                                                                                                              |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 88 |  Shower(s) of snow pellets or small   hail, with or without rain or rain and snow mixed, moderate or heavy                                                                                                                                                                   |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 89 |  Shower(s) of hail, with or without   rain or rain and snow mixed, not associated with thunder, slight                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 90 |  Shower(s) of hail, with or without   rain or rain and snow mixed, not associated with thunder, moderate or   heavy                                                                                                                                                          |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 91 |  Slight rain at time of   observation, Thunderstorm during the preceding hour but not at time of   observation                                                                                                                                                               |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 92 |  Moderate or heavy rain at time of   observation, Thunderstorm during the preceding hour but not at time of   observation                                                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 93 |  Slight snow, or rain and snow   mixed or hail at time of observation, Thunderstorm during the preceding hour   but not at time of observation                                                                                                                               |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 94 |  Moderate or heavy snow, or rain   and snow mixed or hail at time of observation, Thunderstorm during the   preceding hour but not at time of observation                                                                                                                    |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 95 |  Thunderstorm, slight or moderate,   without hail, but with rain and/or snow at time of observation                                                                                                                                                                          |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 96 |  Thunderstorm, slight or moderate,   with hail at time of ob.                                                                                                                                                                                                                |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 97 |  Thunderstorm, heavy, without hail,   but with rain and/or snow at time of observation                                                                                                                                                                                       |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 98 |  Thunderstorm combined with   dust/sandstorm at time of observation                                                                                                                                                                                                          |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| .. image:: /images/pw_symbols/pw-000.png   | 99 |  Thunderstorm, heavy with hail at   time of observation                                                                                                                                                                                                                      |
+--------------------------------------------+----+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+





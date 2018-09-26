# ScxmlEditor

Powerful tool for creating, editing and debugging SCXML charts

## System requirments

Windows 7, 8, 10

You can find portable version **[here](https://www.dropbox.com/sh/fjzm9ejdrtra1c0/AAB_ASgIPRFLX57x7rWPEv3Ta?dl=0)**

![2018-09-24 16 23 50](https://user-images.githubusercontent.com/18611095/45954643-3e30d000-c016-11e8-8f79-205f770af667.png)

## Creating SCXML charts

### Creating a unit
**Unit** is a single scxml chart. It is mostly used for simple charts without invokable sessions.

Select **File**->**New Unit** or press **Shift+Ctrl+N**

### Creating a project
**Project** is the most preferred choice of designing scxml charts to get all benefits (custom triggers, nested scxml charts, etc.)

Select **File**->**New Project** or press **Ctrl+N**

## Editing SCXML charts
**ScxmlEditor** provides a project wizard for opening scxml. It supports either opening files with metainformation about the position of states and transitions or plain scxml files. You can use **ScxmlEditor** to add states and transitions to the chart. You can add executable content to a state chart to enable the state machine to modify its data model and to interact with external entities.

1. Select **File**->**Open Unit** or press **Shift+Ctrl+O** (for all types of .scxml files)
2. Select **File**->**Open Project** or press **Ctrl+O** (for ScxmlEditor .sproj files)

### Property inspector
Is used to edit and examine the properties of the currently selected states, executable contents and transitions.

![2018-09-26 09 50 33](https://user-images.githubusercontent.com/18611095/46062582-eeb3e680-c172-11e8-993b-cedbc270894d.png)

### Editor tabs
Are used to add scxml elements, zoom, align, change chart visual options, etc.

![2018-09-26 09 50 33](https://user-images.githubusercontent.com/18611095/46062784-8c0f1a80-c173-11e8-8fca-8937b9b0b721.png)

## Debugging
**ScxmlEditor** has an ability to listen UDP commands (AfterEnter, BeforeEnter, AfterExit, BeforeExit, Step, BeforeExecContent, AfterExecContent, BeforeInvoke, AfterInvoke, BeforeUnInvoke, AfterUnInvoke, BeforeTakingTransition, AfterTakingTransition, StableConfiguration, BeforeProcessingEvent). **Enter** and **Exit** graphically highlight the corresponding states. You can also trace the execution of the chart and use breakpoints.

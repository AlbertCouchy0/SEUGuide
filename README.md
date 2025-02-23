# Campus Navigation System Based on MFC

## Project Description

This project is a campus navigation system developed using C++ and the MFC framework, based on the Jiulonghu Campus of Southeast University. It aims to provide users with functions such as querying building information, path planning, and campus tour planning.

### Main Features:
1. **Building Information Display**: Buildings are located using a "positioning" button or coordinate method, marked with blue dots on the map, and their information is displayed when the mouse hovers over them.
2. **Road Node Marking**: Road nodes are marked on the map with yellow dots.
3. **Campus Navigation**: The system plans the shortest path from the starting point to the destination using Floyd's algorithm, draws the path on the map, and displays the path length.
4. **Tour Planning**: The system automatically plans the shortest tour route that passes through all selected buildings based on user input and draws it on the map.
5. **Map Operations**: The map supports zooming, panning, and full-screen display to allow users to view detailed information.
6. **Multimedia Integration**: The system includes a music playback function that allows users to play or stop background music.

### Project Highlights:
1. **User-friendly Interface**: The interface is simple and intuitive, with convenient mouse interactions.
2. **Rich Functionality**: In addition to basic navigation, the system also integrates campus tour planning and multimedia display.
3. **Southeast University Elements**: The design incorporates Southeast University's unique elements to enhance user experience.
4. **Optimized Algorithms**: Floyd's algorithm is used for efficient path planning.

### Technical Implementation:
1. The user interface is designed using the MFC framework, including dialog boxes, buttons, text boxes, and other controls.
2. Map display is implemented using the `Picture Control` control, supporting dynamic path drawing and annotations.
3. Mouse interaction functions are implemented through event handlers such as `OnMouseMove()` to display building information and map operations.
4. Floyd's algorithm is used for shortest path calculation, and an adjacency matrix is used to store map data.
5. Music playback is implemented using the `PlaySound` function, supporting loop playback and pause.

### Testing Results:
1. Upon launching, the program enters the welcome interface, where users can choose to enter "Introduction Display" or "Campus Navigation".
2. In the "Introduction Display" interface, hovering the mouse over a building icon displays detailed information about the building.
3. In the "Campus Navigation" interface, users can select a starting point and destination, and the system automatically draws the shortest path and displays the path length.
4. The map supports zooming, panning, and other operations to allow users to view detailed information in different areas.
5. The music playback function works normally, allowing users to control playback and stopping freely.

## Running Steps
### For exe file
1. The browser may report it as unsafe during the download, but you can choose to keep it.
2. Run the file.

### For project files
1. Extract SEUGuide to the project directory.
2. Open `Whole.sln` with VS2010 and click run.

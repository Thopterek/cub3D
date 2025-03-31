Project to recreate the basics used in the first ever FPS game
-
<img width="1272" alt="Cub3D" src="https://github.com/user-attachments/assets/2a2212a0-0d86-4285-83e3-a06e24441844" />
it was made by me and @Rexbrainz, and here is what we are handling:

* keyboard input: W A S D for moving, escape to quit and arrows to rotate point of view

* using textures: each wall has its own png texture that can be easly replaced

* configuring the map: if you obey to the rules of creating it you can add your own

* setting colors: for floors and ceiling you can modify map to set your own in RGB format

* clean start: just run make and then ./cub3D "map_that_you_put_in_the_map_folder.cub"

<img width="1272" alt="huge" src="https://github.com/user-attachments/assets/af933c34-0807-45dd-976e-313ee4140eb2" />
its a simple project but we can handle huge maps per the one above, the work was split:

* I did the parsing part (map handling, errors and textures)

* raycasting we did together but most sources were found by @Rexbrainz

* it compiles with no problem on Mac, the handling on Linux needs modification

Thank you for your attention and hopefully reading the source code can help you out!

- fix text (if possible)

- in memory streaming (or ramfs / tmpfs)

- a queue of frames to render instead of saving all
    - keep track of last frame, current (display)
    - wrapper to handle information about recent captured frame to see when it finished and turn it over as current frame
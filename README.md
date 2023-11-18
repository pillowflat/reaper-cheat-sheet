# REAPER Notes

Notes on how to record MIDI/audio and video for YouTube videos.

### New track (from MIDI/VST template) 
- right-click left track area, 'Insert track from template' -> PianoOne

### New track
- double-click left track area to add new track
- hit record, drag bottom of track down to get to Input.
- Input 
    - MIDI -> All MIDI inputs
- To playback to keyboard
    - select Route -> MIDI Hardware Output and select FA-08
- To playback to VST
    - select FX, All Plugins/Recently Used, pick one of the NeoPiano VSTs
    - Insert piano.ins currently in /Documents/REAPER Media/Piano1.ins

### Add video
- drag video onto tracks section
- Remove audio -> Right-click video track, Source Properties, Audio dropdown -> Disable audio 
- Use Video tab at bottom left to view
- Use Playback Rate dial to slow down to visually sync video with audio

### Video effects
- Fade in/out
    - select FX button, click on the 'All Plugins' header, select 'Video processor'
    - From the dropdown, select 'Basic helpers: Item fades affect video'
    - drag from top/left and top/right corners of video track to fade in/out

### Record audio from audio source during playback of MIDI
- create new track
- IN FX -> set to 'Input Stereo Input 1/Input 2'
- 'in' dropdown -> select 'Record: input (force format)' -> Force stereo
- Increase audio input level from keyboard (FA-08 -> use Output knob)

### Audio effects for a specific track
- click 'FX' button, select 'AU: AUReverb2' for example
- Fade in/out - drag from top/left and top/right corners of audio track

### Render
- File -> Render...
    - Sample rate: 44100 Hz
    - Channels: Stereo
    - Resample mode: Sinc Interpolation: 192pt
    - Format: MPEG-4
    - Size: 1920 x 1080
    - Framerate: 30
    - Video: H.264, 2048 kbps
    - Audio: AAC, 128 kbps

### Tips
- Slow down playback on all tracks
    - 'Playback Rate' dial at bottom right-hand side of tracks
- Slow down playback on individual tracks
    - Right-click track, Item Properties, Playback rate

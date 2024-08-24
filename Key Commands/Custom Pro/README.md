# "Custom Pro" Keybindings

This is my main (current) keybinding file.

Commands Shortcuts Table
:-:
<kbd>⇧</kbd>
<kbd>^</kbd>
<kbd>⌥</kbd>
<kbd>⌘</kbd>
<kbd>↩</kbd>
<kbd>⌫</kbd>
<kbd>▲</kbd>
<kbd>▶</kbd>
<kbd>▼</kbd>
<kbd>◀</kbd>




## Custom Commands

### <kbd>T</kbd> - Split Regions / Events at Playhead Position

This is customised from the default (<kbd><kbd>⌘</kbd> <kbd>T</kbd></kbd>) shortcut, making it faster and easier to use.
If the a region is at the very edge of the playhead (i.e. if starts / ends at the playhead), then running splitting that region won't have any effect.

This is useful for quickly chopping up an audio / MIDI file (e.g. to reset the audio tail / chop it up / etc.).



### <kbd><kbd>⇧</kbd> <kbd>,</kbd></kbd> (<kbd><kbd>&lt;</kbd></kbd>) - Go To Previous Marker
### <kbd><kbd>⇧</kbd> <kbd>.</kbd></kbd> (<kbd><kbd>&gt;</kbd></kbd>) - Go To Next Marker

When using Markers, these allow you to navigate to the next / previous marker. This is very useful for quickly jumping between different points.



### <kbd><kbd>⌥</kbd> <kbd>▼</kbd></kbd> - Transpose KeySignature/Chord/Region Event -1 Semitone, Mudge Automation Down 1 Step or Move Marquee Top Down 1 Track
### <kbd><kbd>⌥</kbd> <kbd>▲</kbd></kbd> - Transpose KeySignature/Chord/Region Event +1 Semitone, Mudge Automation Up 1 Step or Move Marquee Top Up 1 Track
### <kbd><kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>▼</kbd></kbd> - Transpose Region/Event -12 Semitone, Nudge Automation Down 10 Steps or Move Marquee Bottom Down 1 Track
### <kbd><kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>▲</kbd></kbd> - Transpose Region/Event +12 Semitone, Nudge Automation Up 10 Steps or Move Marquee Bottom Up 1 Track

These are all useful for quickly transposing regions / MIDI events.

- When a MIDI / Audio Region is selected, using these commands will transpose it up / down by 1 or 12 semitones.
- When a MIDI Event in the Piano Roll Editor is selected, using these commands will transpose it up / down by 1 or 12 steps.

> [!note]
> Some tracks (usually Drum instrument tracks) are set to have "No Transpose", in this case, when these commands are used on the region, the region will still show transposition, but the track will be unaffected.

> [!note]
> Regions can have ±96 semitones transposition.


### <kbd><kbd>⌘</kbd> <kbd>⇧</kbd> <kbd>T</kbd></kbd> - Move Selected Regions to Focused Tracks

Moves all the selected regions to the currently focused track. There can only be one focused track at a time.
The currently focused track is indicated with a light colour on the edge of the track.

[Demonstration of Currently Focused Track](https://github.com/user-attachments/assets/cba436eb-cbb8-4814-b993-a95fc688df76)

This is useful after bouncing regions from a split-up region, to merge all the regions onto the same track.



### <kbd><kbd>⌘</kbd> <kbd>⇧</kbd> <kbd>&#91;</kbd></kbd> (<kbd><kbd>⌘</kbd> <kbd>&#123;</kbd></kbd>) - Set Next Lower  Division
### <kbd><kbd>⌘</kbd> <kbd>⇧</kbd> <kbd>&#93;</kbd></kbd> (<kbd><kbd>⌘</kbd> <kbd>&#125;</kbd></kbd>) - Set Next Higher Division

This changes the division value, which affects how other key commands such as `Forward / Rewind by Division Value` and `Nudge Region/Event Position Left/Right by Division` work.

For example, this could be combined with `Split Regions/Events at Playhead Position` to quickly split up an audio region into parts.

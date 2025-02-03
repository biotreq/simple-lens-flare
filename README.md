
![flare](https://github.com/user-attachments/assets/21dccdbc-9119-4c80-a24e-eb2666319f72)

A simple lens flare shader for Godot, similar to lens flare effects as seen in late 90s games. Inspired mainly by the 1999 AvP game (or a vague memory thereof).

Included are two examples of the shader, with a bit different effects indended for mixing and matching (billboard with or without keeping scale, distance fade). The main feature is that it disappears when the center of the lens flare is hidden behind something, and is otherwise drawn on top of other objects.

Should it be placed inside a mesh (a lamp for example), the enclosing mesh should not write to the Z-buffer - preferably, it should be transparent itself, using alpha transparency or similar.

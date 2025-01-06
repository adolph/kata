# Session

```bash
# Session: A collection of windows. Sessions can be created, attached, or detached.

# New Session
tmux new -s session_name

# Detach from session
# meta is control+b
<meta> d or <meta> :detach

# Rename session
<meta> $

# List sessions
tmux list-sessions

# Start new or Attach to named session
tmux new -A -s session_name

# Stop session
tmux kill-session -t session_name

```

# Window

```bash
# Window: A container for panes. Windows can be split into multiple panes.

# New session with named window
tmux new -s mysesh -n mywin

# Create window
# meta is control+b
<meta> b

# Rename window
<meta> ,

# Close window
<meta> &

# List windows
<meta> w

# Next
<meta> n

# Previous
<meta> p

# Last active
<meta> l

# By ID number
<meta> [0-9]

```

# Pane: A single terminal session within a window. Panes can be resized, moved, or closed.

```bash
# New horizontile split
<meta> "

# New vertical split
<meta> %

# List 
<meta> q

# Switch to by position
<meta> <arrow key>

# Next
<meta> o

# By ID Number
<meta> q [0-9]

# Close current
<meta> x

```

# Concepts

Client: Attaches a tmux session from an outside terminal such as xterm.

Session: A collection of windows. Sessions can be created, attached, or detached.

Window: A container for panes. Windows can be split into multiple panes.

Pane: A single terminal session within a window. Panes can be resized, moved, or closed.


https://tmuxcheatsheet.com/

https://github.com/tmux/tmux/wiki/Getting-Started



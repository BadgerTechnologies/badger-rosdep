# Badger custom rosdep
This provides a place to store custom rosdep modifications. This is needed for
packages that exist outside of the standard ubuntu/ros package repositories. It
is also useful for python packages that we either need to pip at a specific
version or need to pull from pip instead of apt.

New packages should only be added here if they cannot reasonably be added to
the upstream rosdep files at https://github.com/ros/rosdistro .

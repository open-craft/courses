# OpenCraft Courses

![OpenCraft Logo](opencraft-logo.png)

This repository contains all the courses that are publically available on courses.opencraft.com.

## How to add a new course to this repository

1. Type `git checkout --orphan xblock-name` to create a new "orphan" branch.
1. Delete any files that remain present/staged.
1. Export the course from Studio.
1. Extract the contents of the resulting tarball into this repository.
1. Ensure that the course is not in a subfolder. `course.xml` should be in the
   root of the repository.

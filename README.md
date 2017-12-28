# OpenCraft Courses

![OpenCraft Logo](opencraft-logo.png)

This repository contains all the courses that are publically available on courses.opencraft.com:

* [**Onboarding course**](https://courses.opencraft.com/courses/course-v1:OpenCraft+onboarding+course/about): Download [onboarding.tar.gz](https://github.com/open-craft/courses/archive/onboarding.tar.gz) (`course-v1:OpenCraft+onboarding+course`) or [browse source](https://github.com/open-craft/courses/tree/onboarding).

## How to add a new course to this repository

1. Type `git checkout --orphan xblock-name` to create a new "orphan" branch.
1. Delete any files that remain present/staged.
1. Export the course from Studio.
1. Extract the contents of the resulting tarball into this repository.
1. Ensure that the course is not in a subfolder. `course.xml` should be in the
   root of the repository.

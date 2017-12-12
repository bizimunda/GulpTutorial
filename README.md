# GulpTutorial
This tutorial is about Gulp. How to create Gulp project and run its tasks.

First create a folder GulpProject

Open it in the VS

run command npm init

hit enter couple of times

run command npm install --save-dev gulp

create folder src
create file in src gulpfile.js

-- top level functions

gulp.task - define tasks

gulp.src -point to files to use

gulp.dest - points to folder to output

gulp.watch - watch files and folders for changes

--save this function in gulpfile.js

gulp.task('message', function(){
return console.log("gulp is running");
});

--and run in vs --->gulp message

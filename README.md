# remove all files/directories except those ending with .log or .sh
ls | grep -Ev '\.log$|\.sh$' | xargs rm -r

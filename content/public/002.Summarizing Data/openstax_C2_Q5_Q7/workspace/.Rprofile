setHook("rstudio.sessionInit", function(newSession) {
  file.edit("student.R")
  assign("x", read.csv("data.csv"), envir = globalenv())
}, action = "append")

if (Sys.getenv("CI") == "") {
  source("renv/activate.R")
  if (.Platform$OS.type == "windows") {
    .libPaths(unique(c(.libPaths(), file.path(Sys.getenv("LOCALAPPDATA"), "R/win-library/4.3"))))
  }
}

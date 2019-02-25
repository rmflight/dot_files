options(repos=structure(c(CRAN="https://cloud.r-project.org")),
        devtools.desc.author = 'person(given = c("Robert", "M"), family = "Flight", email = "rflight79@gmail.com", role = c("aut", "cre"))',
        devtools.desc.license = "MIT",
        blogdown.author = "Robert M Flight",
        blogdown.ext = ".Rmd",
        blogdown.subdir = "post",
        servr.daemon = TRUE)

setHook(packageEvent("grDevices", "onLoad"),
function(...) grDevices::X11.options(type='cairo'))
options(device='x11')

q = function (save = 'no', ...) base::q(save = save, ...)

#makeActiveBinding("refresh", function() { system("R --no-save"); q("no") }, .GlobalEnv)

setHook("rstudio.sessionInit", function(newSession) {
  if (newSession){
    if( is.null(rstudioapi::getActiveProject()) ){
    rstudioapi::openProject("/home/rstudio/fischerRRR-manuscript")
  }


}
  if(rstudioapi::getActiveProject() == "/home/rstudio/fischerRRR-manuscript"){
    rstudioapi::navigateToFile("README.md")
  }
}, action = "append")

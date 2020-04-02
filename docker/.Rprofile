setHook("rstudio.sessionInit", function(newSession) {
  if (newSession){
    if( is.null(rstudioapi::getActiveProject()) ){
    rstudioapi::openProject("/home/rstudio/attentional_snarc")
  }


}
  if(rstudioapi::getActiveProject() == "/home/rstudio/attentional_snarc"){
    rstudioapi::navigateToFile("README.md")
  }
}, action = "append")

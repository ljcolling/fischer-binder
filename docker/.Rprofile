setHook("rstudio.sessionInit", function(newSession) {
  if (newSession){
    if( is.null(rstudioapi::getActiveProject()) ){
    rstudioapi::openProject("/home/rstudio/fischerRRR-manuscript")
  }
}
}, action = "append")

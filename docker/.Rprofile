setHook("rstudio.sessionInit", function(newSession) {
   if (newSession){
     if( is.null(rstudioapi::getActiveProject()) ){
     rstudioapi::openProject("/home/jovyan/my_rproject")
   }


}
   if(rstudioapi::getActiveProject() == "/home/jovyan/my_rproject"){
     #rstudioapi::navigateToFile("README.md")
   }
}, action = "append")

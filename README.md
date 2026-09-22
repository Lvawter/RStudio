#install packages before
library(tidyr)
library(ggplot)
library(udpipe)

# change the language to german 
m_ger <- udpipe::udpipe_download_model(language = "german-gsd")

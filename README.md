# Assignment05

# A timed example of readr::read_csv()
### Run as a block of text to time #########
ptm <- proc.time()
DF <- read.csv("UNRATE.csv", col_names=TRUE)
READR_READ_TIME <- (proc.time() - ptm)
READR_READ_TIME
############################################

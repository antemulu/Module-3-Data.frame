# Module-3-Data.frame
R programming 
 Name <- c("Jeb", “Donald”, "Ted”, “Marco” “Carly”, “Hillary”, “Berine”)

> ABC political poll results <- c(4, 62 51, 21, 2, 14, 15)

> CBS political poll results <- c(12, 75, 43, 19, 1, 21, 19)



Name <- c("Jeb", "Donald", "Ted", "Marco", "Carly", "Hillary", "Berine")



 ABC <- c(4, 62, 51, 21, 2, 14, 15)



 CBS <- c(12, 75, 43, 19, 1, 21, 19) 



 #Combine R Objects by Rows or Columns using cbind function  

 

 results <- cbind(Name, ABC, CBS)

 results



 results <- cbind(Name, ABC, CBS)

> Name <- c("Jeb", "Donald", "Ted", "Marco", "Carly", "Hillary", "Berine")

>  ABC <- c(4, 62, 51, 21, 2, 14, 15)

>  CBS <- c(12, 75, 43, 19, 1, 21, 19) 

>  results <- cbind(Name, ABC, CBS)

>  results

  

     Name      ABC  CBS 

[1,] "Jeb"     "4"  "12"

[2,] "Donald"  "62" "75"

[3,] "Ted"     "51" "43"

[4,] "Marco"   "21" "19"

[5,] "Carly"   "2"  "1" 

[6,] "Hillary" "14" "21"


[7,] "Berine"  "15" "19"

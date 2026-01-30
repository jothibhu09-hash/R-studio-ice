# R-studio-ice
icecream<-data.frame(Day=1:10,
                     Temperature=c(28,29,30,31,32,33,34,35,36,37),
                     sales=c(120,135,150,165,180,205,230,260,290,320)
                     )
plot(icecream$Temperature, icecream$sales,
     xlab = "Temperature",
     ylab = "Sales",
     type = "b")
)
plot(icecream$Day, icecream$sales,
     type = "l", 
     xlab = "Day",
     ylab = "Sales",
     main = "Sales over Time",
     col = "red"
     ) 
barplot(icecream$sales,
        names.arg = icecream$Day,
        xlab = "Day",
        ylab = "Sales",
        main = "Sales by Day",
        col = "lightblue")  
avg_sales<- mean(icecream$sales)
    avg_sales



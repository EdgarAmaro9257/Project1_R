library(ggplot2)

# Perform linear regression analysis on WorldHits dataset
perform_regression <- function(data) {
  model <- lm(Duration ~ Year, data = data)
  return(summary(model))
}

# Visualize the relationship between Year and Duration
plot_relationship <- function(data) {
  p <- ggplot(data, aes(x = Year, y = Duration)) +
    geom_point() +
    geom_smooth(method = "lm", se = FALSE) +
    labs(
      title = "Relationship between Year and Duration",
      x = "Year",
      y = "Duration"
    )
  return(p)
}

# Perform descriptive analysis on WorldHits dataset
perform_descriptive_analysis <- function(data) {
  summary_stats <- data %>%
    summarise(
      mean_duration = mean(Duration, na.rm = TRUE),
      median_duration = median(Duration, na.rm = TRUE),
      sd_duration = sd(Duration, na.rm = TRUE),
      var_duration = var(Duration, na.rm = TRUE),
      n = n()
    )
  
  return(summary_stats)
}
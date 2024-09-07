# analysis/main_analysis.R

# Load necessary functions
source("../Project1_MusicTracks/R/load_data.R")
source("../Project1_MusicTracks/R/descriptive_analysis.R")
source("../Project1_MusicTracks/R/regression_analysis.R")

# Load the WorldHits dataset
data <- load_worldhits()

# Perform descriptive analysis
desc_stats <- perform_descriptive_analysis(data)
print(desc_stats)

# Perform regression analysis
regression_result <- perform_regression(data)
print(regression_result)

# Plot the relationship between Year and Score
p <- plot_relationship(data)
print(p)

# Save the plot as an image
ggsave("../output/year_duration_relationship.png", plot = p)

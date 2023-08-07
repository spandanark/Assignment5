``` py
# Merge the datasets based on a common key column
merged_df = pd.merge(df1, df2, on='video_id')

# Save the merged DataFrame to a new CSV file
merged_df.to_csv('/Users/spandanarajamahanthi/Downloads/merged_dataset.csv', index=False)

print(merged_df.head())

```

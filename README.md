# Big-Data-ETL

# Part 1
Upload the part_one_starter_code.ipynb into Google Colab and create a duplicate of this file.

Explore the Amazon Reviews Links to an external site.datasets and pick two datasets to perform ETL.

Rename each part_one_starter_code.ipynb file according to the dataset you are using. For example, if you are going to use the Video Game reviews Links to an external site.file, rename file, part_one_video_games.ipynb. Repeat the process for the duplicate file you created in Step 2.

# RDS Instance

![image](https://user-images.githubusercontent.com/107616415/212657968-db40abce-605d-4ce5-ab57-18769dab42e2.png)



# Extract the Data

Read in each dataset using the correct header and sep parameters.

Get the number of rows in each dataset.

# Transform the Data

For each dataset use the schema.sql file located in the Resources folder of the Starter_Code.zip file to create the four DataFrames as follows:

Create the "review_id_df" DataFrame with the appropriate columns and data types.

Create the "products_df" DataFrame that drops the duplicates in the "product_id" and "product_title columns.

Create the "customers_df" DataFrame that groups the data on the "customer_id" by the number of times a customer reviewed a product.

Create the "vine_df" DataFrame that has the "review_id", "star_rating", "helpful_votes", "total_votes", and "vine" columns.

# Load the Data into an RDS Instance

Export each DataFrame into the RDS instance to create four tables for each dataset.

Load the Data into an RDS Instance


## Dataset-1-Tools: 
https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Tools_v1_00.tsv.gz

### review_id_table_tools

![image](https://user-images.githubusercontent.com/107616415/212656881-aefe3b15-b824-4fc4-bc9a-67a0f4daf642.png)

 


### products_tools


![image](https://user-images.githubusercontent.com/107616415/212656969-3ed8ef24-1aaa-4cab-9c63-516289321595.png)
 


### customers_tools


![image](https://user-images.githubusercontent.com/107616415/212657074-a00ea06c-87a8-47b8-913e-c5346d5cf5e9.png)

 

### vine_table_tools


![image](https://user-images.githubusercontent.com/107616415/212657148-185f7a3f-7128-4989-ab81-ad6bf07daaf5.png)

 



## Dataset-2-Toys: 
https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Toys_v1_00.tsv.gz

### review_id_table_toys
 
![image](https://user-images.githubusercontent.com/107616415/212657220-9f082272-4039-4734-b102-2f72e394d5d7.png)



products_toys

![image](https://user-images.githubusercontent.com/107616415/212657263-3085d7d9-1f44-4163-8df2-147bfe8e2138.png)


 

customers_toys

![image](https://user-images.githubusercontent.com/107616415/212657286-867fe22f-9433-410a-a995-00f92a206b3b.png)

 


vine_table_toys

 ![image](https://user-images.githubusercontent.com/107616415/212657300-f008a091-5e0a-4e14-b506-229376357401.png)



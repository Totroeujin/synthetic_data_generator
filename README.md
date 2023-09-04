# synthetic_data_generator

Reference from:

GitHub repo:
https://github.com/alexppppp/synthetic-dataset-object-detection

and made a few changes such as:
1. Auto-masking        - Only needed to drop /data/{obj_name}/images folder that contains instances wanted to use for synthetic image dataset.
2. Classes.txt         - Classes.txt file being created and put into the /dataset file automatically, allows convenient upload to website like Roboflow.
3. Data with date time - Data now generated with date time and sequence number to enable combine of multiple dataset together quickly.
4. Out-of-bound adjust - Able to determine if wanted the instance being appear half/not-fully or definitely full image being place at create_composite()
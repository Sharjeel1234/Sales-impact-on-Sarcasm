Selected Home and Furniture Category from Amazon and 
then filter out 4 star and up initially to search all products in this category.

Further given URL path of same filtered page to the ZONASINHUNTER 2 to scap all product
with candidate attibutes which further refined into desireable attributes.

DataSet further can be merge with other categories such as

Lighting

Stationary & Office Supplies

Others.

Further we have plan to extend the dataset and make it available to public society under different categories.


Total it contain 371 Products and 1432 reviews filter based on min of 5% discount
and more than 3 reviews.



Processedfiles under Refined-final
refined-1-1.5star.csv   -  188 reviews
refined-2-2.5star.csv   -  88 reviews
refined-3-3.5star.csv   -  157 reviews
refined-4-5star.csv   -    1030 reviews


The reviews which have negative sentiment score and further manually validated and filtered from the site https://deepmoji.mit.edu/.
Take all reviews from 4 star , 3 star and check confidance score more than medium or equal after selecting only negative reviews because
these have more potential to sarcasm. The validated reviews pass to keras model for prediction with all impact factors of sales. The sarcastic reviews have worse impact which is our initial finding of the project.

Further, Irony and its types will be tested with SemEval2018-Task3 review features traning. Stay tune shortly!

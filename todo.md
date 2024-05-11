# För båda nivåerna skall följande punkter och frågor behandlas:
Det är godkänt att rita ut i både 2 dimensioner och 3 dimensioner
Använd bara PCA för att rita ut klustrena

- [ ] Skriv en egen K-Means
- [ ] För varje dataset
    – [ ] Analysera datan
        – [ ] Innehåller datan konstiga värden?
        – [ ] Ska några attribut plockas bort?
        – [ ] Behövs datan normaliseras?
    – [ ] Träna din K-Means (experimentera med K)
    – [ ] Rita ut klustrena

# Dataset för godkänt:
small iris.csv

# Väl Godkänt
iris.csv
Mall Customers.csv

The K-means algorithm is an algorithm used in machine learning. It takes unlabeled, unclassified data and groups them into clusters based on how similiar/different the data is. It works by taking a predetermined number K amount of clusters and computing so called centroids. It starts by deciding K centroids as K random points. After that, it calculates the distance between the centroids and all the other points in the data set, and picks for each centeroid which data point is the closest. The chosen data points are determined to belong to the cluster of that each centeriod represents. New positions are determined for the centroids by calculating the avarage position of each cluster. If the positions of the centroids have changed, the process of finding the closest points is repeated until we reach a stage where the centroids no longer change position
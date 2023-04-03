
</p>
<h1 align="center"> <i>Netflix Movies and TV Shows Clustering</i></h1>
<h2 align="center">(Unsupervised Machine Learning) </i></h2>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter <img width="664" alt="image_19400_1_5042248765" src="https://user-images.githubusercontent.com/121742479/229417541-62236170-e834-4584-a0f6-d810f287772e.png"></a> </h3>

><p>Netflix Recommender recommends Netflix movies and TV shows based on a user's favorite movie or TV show. It uses a  a K-Means Clustering model to make these recommendations. These models use information about movies and TV shows such as their plot descriptions and genres to make suggestions..</p>

<h2>____________________________________________________________________________________</h2>
<h2><b>Contents:</b></h2>
<ol>
  <li>Exploratory Data Analysis</li>
  <li>Understanding what type content is available in different countries</li>
  <li>Is Netflix increasingly focusing on TV rather than movies in recent years.</li>
  <li>Clustering similar content by matching text-based features</li>
</ol>
<h2>____________________________________________________________________________________</h2>
<h2><b>Dataset:"2019 Netflix Movies  And Tv Show" obtained from Flixable,a third party search engine </b></h2>
<h2>____________________________________________________________________________________</h2>
<h3><b>Data Description:</b></h3>
The dataset consists of listings of all the movies and tv shows available on Netflix, along with details
such as - cast, directors, ratings, release year, duration, etc
<ul>	
			<li> show_id : Unique ID for every Movie / Tv Show</li>
			<li> type : Identifier - A Movie or TV Show</li>
			<li> title : Title of the Movie / Tv Show</li>
			<li> director : Director of the Movie</li>
			<li> cast : Actors involved in the movie / show</li>
			<li> country : Country where the movie / show was produced</li>
			<li> date_added : Date it was added on Netflix</li>
			<li> release_year : Actual Release Year of the movie / show</li>
			<li> rating : TV Rating of the movie / show</li>
			<li> duration : Total Duration - in minutes or number of seasons</li>
			<li> listed_in : Genre</li>
			<li> description: The Summary description</li>
</ul>


<h2>____________________________________________________________________________________</h2>
<h2> :pen: K-means Clustering </h2>
<p> k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can be found using k-medians and k-medoids.

<h2>____________________________________________________________________________________</h2>

<h2> :pen: Agglomerative Hierarchical Clustering </h2>
<p> The agglomerative hierarchical clustering algorithm is a popular example of HCA. To group the datasets into clusters, it follows the bottom-up approach. It means, this algorithm considers each dataset as a single cluster at the beginning, and then start combining the closest pair of clusters together. It does this until all the clusters are merged into a single cluster that contains all the datasets.
This hierarchy of clusters is represented in the form of the dendrogram.

<h2>____________________________________________________________________________________</h2>


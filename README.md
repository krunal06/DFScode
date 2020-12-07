this code implements dfs algorithm with edges type.
first it will take a array of arraylist and create a graph by adding adjacency list on by one. 
after we will call DFS function after creating an object of GraphDFS class. and also will print out a result of dfs search with timestamp and also with edges type.
DFS function will find new vertices and color them with white.also it will call visitDFS function after finding first white vertex.
visitDFS will take that vertex and add it to a result to make a color gray. increase a time and make it to a first timestamp of u.
it will process all vertexes like described in an algorithm and print edges type according to color and timestemp properties.
After all processes are done, it will print a result with timestemp and edges type.

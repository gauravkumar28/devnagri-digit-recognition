***************			READ ME				************


Dataset of HIndi numerals can be found in "data.mat" and its labels in "label.mat".

On loading "data.mat" and "label.mat" in matlab(using "load('data.mat');"). You will get two matrices data and label .

data :
It is ( 28 X 615132 ) matrix.
So our i th image will be data(1:28,28*(i-1)+1:28*i) .

label is ( 1 X 21969 ) matrix.
So label for i th image will be label(i) .



If you want to extract images from this :

1.Create 10 folders with names from 0 to 9 in the working directory.
2. Run getimages.m

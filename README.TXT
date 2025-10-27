27. public void playArtistSamples(String artist)
    {
        boolean found = false;
        for(String filename : files) {
            if(filename.contains(artist)) {
                System.out.println(filename);
                player.playSample(filename);
                found = true;
            }else{
                System.out.println("No songs found");
            }
        }
    }
28. for (Track track : trackList) {
    
}
Lab 7 Part 2:
23. public void listWithIndex()
    {
       for(int i = 0; i < files.size(); i++) {
            System.out.println(i + ":" + files.get(i));
        } 
    }
24. copyOfRange: copies a specified range of elements from an existing array into a new array
    binarySearch: searches for a specific value in a sorted array and returns its index
    fill: assigns every element of an array with a specified value
    sort: arrange elements in a specific order
25. int[] numbers = {5, 2, 6, 7, 3};

    int[] part = Arrays.copyOfRange(numbers, 1, 4);
    Arrays.sort(numbers);
    int index = Arrays.binarySearch(numbers, 3);
    Arrays.fill(numbers, 0);
    
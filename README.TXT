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
23. 
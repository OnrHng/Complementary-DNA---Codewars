# Complementary-DNA---Codewars

In DNA strings, symbols "A" and "T" are complements of each other, as "C" and "G". You have function with one side of the DNA; you need to get the other complementary side. DNA strand is never empty or there is no DNA at all 

for example 
          DNAStrand ("ATTGC") // return "TAACG"
          DNAStrand ("GTAT") // return "CATA" 
          
        function DNAStrand(dna){
         var  complement = '';
          for ( var i = 0 ; i < dna.length ; i++) {
            if (dna[i] === 'A') {
              complement = complement + 'T';}
            else if (dna[i] ==='T'){
              complement = complement + 'A';}
            else if (dna[i] ==='C'){
              complement = complement + 'G';}
            else if (dna[i] ==='G'){
             complement = complement +'C';}   
            }
           return complement ;
            }
Best;)

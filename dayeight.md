
# Why are loops used
    loops in javascript are used to get a message across without haveing to rewrite the same code over and over.


## Example of while loop

    function famous(){
    let answer = 0;
    while(answer < 2){
        let answerFamous = prompt('name a famous story from seattle');
        if(answerFamous === 'bigfoot'){ return answerFamous}
        else if (answerFamous !== 'big foot') 
       
        {
    alert('try again');
    answer++;}
        }
} 
famous(); 

## Example of for loop

    for(let i = 0; i< 2; 1++){
     if(i ===3) break; 
 console.log('i');
    
    }

    
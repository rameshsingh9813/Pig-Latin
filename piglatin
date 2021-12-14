function  translatePigLatin(str){
    let k=str.split('');
    let j=['a','e','i','o','u'];
    let p=0;
    for(let i in j){
        if(k[0]==j[i]){
             p+=1;
            break;
        }
    }
    if(p>0){
        return k.join('')+'way'
    }
    else{
        return k.slice(1).join('')+k[0]+'ay'
    }
}

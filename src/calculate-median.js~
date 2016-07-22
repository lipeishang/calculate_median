function calculate_median(arr) {
    var even=findEven(arr);
    var put=findMedian(even);
    return put;
}

function findEven(arr) {
    var even=[];
    var j=0;

    for(var i=1;i<arr.length;i+=2){
        even[j]=arr[i];
        j++;
    }

    return even;
}

function findMedian(even) {
    var out;

    if(even.length%2===0){
        out=(even[((even.length-1)/2-1).toFixed(0)]+even[((even.length+1)/2-1).toFixed(0)])/2;
    }
    else {
        out=even[(even.length-1)/2];
    }

    return out;
}


module.exports = calculate_median;

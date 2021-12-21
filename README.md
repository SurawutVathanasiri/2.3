# 2.3
<head>

</head>
<body>
    <script>
    console.log(range(1,10,1))
    console.log(range(5,2,-1))
    console.log(sum(1,10,1))
    console.log(sum(5,2,-1))
    function range(start,end,array){
        var x = []
        if(start < end){
            for(let i = start; i <= end; i += array){
                x.push(i)
            }
        }else if(start > end){
            for(let i = start; i >= end; i += array){
                x.push(i)
            }
        }
        return x
    }
    function sum(start,end,array){
        var sumall = 0
        if(start < end){
            for(let j = start; j <= end; j += array){
                sumall += j
            }
        }else if(start > end){
            for(let j = start; j >= end; j += array){
                sumall += j
            }
        }
        return sumall
    }
    
    </script>
</body>

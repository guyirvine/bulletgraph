#Bulletgraph

An html version of Stephen Few's [Bullet graph](http://en.wikipedia.org/wiki/Bullet_graph).


##Install
> bower install bulletgraph



##Usage

> bullet_graph( id, options )

See index.htm for example usage, but this,

    <div id="g3"></div>
    <script>
    bullet_graph( "g3",
             {
                "ticks": 5,
                "range": [70,90,100],
                "measure": 55,
                "target": 80
             });
    </script>

will get you going.



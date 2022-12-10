# NewCodingBOT
New Repository
<!DOCTYPE html>
<html>
    <head>
        <style>
            .item1{grid-area: header;}
            .item2{grid-area: menu;}
            .item3{grid-area: main;}
            .item4{grid-area:right}
            .item5{grid-area: footer;}
            
            .grid-container{
                display: grid;
                grid-template-areas:
                'header header header header header header'
                'menu main main main right right'
                'menu footer footer footer footer footer';
            grid-gap:10px;
            background-color: antiquewhite;
            padding: 10px;
            }
            .grid-container > div{
                background-color: rgb(225,255,255);
                text-align: center;
                padding: 20px;
                font-size: 30px;
            }
        </style>
    </head>
    <body>
        <div class="grid-container">
            <div class="item1">Header</div>
            <div class="item2">Menu</div>
            <div class="item3">Main</div>
            <div class="item4">Right</div>
            <div class="item5">Footer</div>
            
            
        </div>
    </body>
</html>.

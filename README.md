# How to Add Particleground
- Go to the [project's GitHub](https://github.com/jnicol/particleground)
- Click the green clone or download button and copy the link
- In your terminal run
        
        git clone https://github.com/jnicol/particleground.git

- Add this to your `script.js`

      $('body').particleground();
      
- Add this to you `style.css`
    
      body {
        width: 100vw;
        height: 100vh;
      }

      canvas {
        position: fixed;
        top: 0;
        left: 0;
        z-index: -1;
      }
 - Play with some of the configuration options in `script.js`
 
              $('body').particleground({
                dotColor: '#ff0000',
                lineColor: '#00ff00',
                minXSpeed: .1,
                maxXSpeed: .2,
                minYSpeed: .1,
                maxYSpeed: .2,
                directionX: 'right',
                directionY: 'top',
                density: 4000,
                particleRadius: 4,
                lineWidth: 1,
                curvedLines: true,
                proximity: 50,
                parallax: true,
                parallaxMultiplier: 10, 

              });

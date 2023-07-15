    after:   var collidingLadder = null;
    
    function keyPressed(e) {
          if (e.code == "Numpad1") {
            console.log(
              parseInt(ladder.style.bottom),
              parseInt(player.style.bottom)
            );
          }
        }
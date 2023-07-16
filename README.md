# Donkey Kong Re-Imagined!

# instant push copy paste all below in one go:

git init
git branch -M main
git add .
git commit -m "update"
git push -u origin main

push up to github reminder:
git init
git branch -M main
git add .
git remote add origin https://github.com/bigBagBoogy/DonkeyKong_Re-imagined.git
git commit -m "first commit"
git push -u origin main

# read position during game:

     after:   var collidingLadder = null;

    function keyPressed(e) {
          if (e.code == "Numpad1") {
            console.log(
              parseInt(ladder.style.bottom),
              parseInt(player.style.bottom)
            );
          }
        }

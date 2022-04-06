# <span style="color: biege;">Super Mario Implementation in Python</span>

## <span style="color: red;">Running</span>

- $ pip install -r requirements.txt
- $ python main.py

## <span style="color: red;">Standalone windows build</span>

- $ pip install py2exe
- $ python compile.py py2exe

## <span style="color: red;">Controls</span>

- Left: Move left
- Right: Move right
- Space: Jump
- Shift: Boost
- Left/Right Mouseclick: secret

## <span style="color: red;">Current State</span>

![Alt text](img/pics.png "current state")

## <span style="color: red;">Dependencies</span>

- pygame
- scipy

## <span style="color: red;">Correct All .png Issues (RUN ALL CODE AT ONCE)</span>

for f in $(find . -type f -name "\*.png")
do
echo "Processing $f ..."
convert $f -strip $f
done

## <span style="color: yellow;">Contributions</span>

I, Terrell D Lemons, want to give all the credit to a **Super Mario Bros** Tutorial in Udemy

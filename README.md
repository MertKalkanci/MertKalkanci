### My whole life is something about 4 wheels and a computer

```cs
public class TireSetting
        {
            public AnimationCurve FrictionCurve;
            [Space]
            public WheelFrictionCurve curve;
            public float extremiumSlip, asymptoteSlip, stiffnes;
            
            public void Configure()
            {
                curve = new WheelFrictionCurve();
                curve.asymptoteSlip = asymptoteSlip;
                curve.asymptoteValue = FrictionCurve.Evaluate(asymptoteSlip);
                curve.extremumSlip = extremiumSlip;
                curve.extremumValue = FrictionCurve.Evaluate(extremiumSlip);
                curve.stiffness = stiffnes;
            }

        }       
```

A Chevrolet Corvette C7.R passing 2016 Ford GT Le Mans

![(Corvette Racing)](https://i.pinimg.com/736x/03/7a/b1/037ab13ceb7054fb7cc0510b463ebdce--corvettes-vs.jpg)

[![Mail Badge](https://img.shields.io/badge/mertkalkanci79@gmail.com-ff5050?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:mertkalkanci79@gmail.com)](mailto:mertkalkanci79@gmail.com)

### My whole life is something like 4 wheels and a computer

```cs
public AnimationCurve FrictionCurve;
            [Space]
            public WheelFrictionCurve curve;
            public float extremiumSlip, asymptoteSlip, stiffnes;
            
            public void ConfigureTires()
            {
                curve = new WheelFrictionCurve();
                curve.asymptoteSlip = asymptoteSlip;
                curve.asymptoteValue = FrictionCurve.Evaluate(asymptoteSlip);
                curve.extremumSlip = extremiumSlip;
                curve.extremumValue = FrictionCurve.Evaluate(extremiumSlip);
                curve.stiffness = stiffnes;
            }
```
[![Mail Badge](https://img.shields.io/badge/mertkalkanci79@gmail.com-ff5050?style=for-the-badge&logo=gmail&logoColor=white&link=mailto:mertkalkanci79@gmail.com)](mailto:mertkalkanci79@gmail.com)

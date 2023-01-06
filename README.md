### My whole life is something like 4 wheels and a code editor

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

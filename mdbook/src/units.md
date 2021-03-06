# Units

Dewy was designed from day 1 to include physical units such as kilogram, meter, second. 

## A Simple Example

Using units is quite straightforward, as they can be included in just about any regular math expression

```dewy
mass = 10 kg
velocity = 30 m/s
energy = 1/2 * mass * velocity^2
```

The `energy` variable now contains a value of `9000 joules`.

## (TODO->rest of units features + examples)

## Full List of Units

(TODO->maybe like solidworks, allow user to set unit system, e.g. meters-kilograms-seconds, centimeters-grams-seconds, etc. See: https://en.wikipedia.org/wiki/MKS_system_of_units https://en.wikipedia.org/wiki/Metre%E2%80%93tonne%E2%80%93second_system_of_units https://en.wikipedia.org/wiki/Foot%E2%80%93pound%E2%80%93second_system https://en.wikipedia.org/wiki/Centimetre%E2%80%93gram%E2%80%93second_system_of_units )

### Base Units
Abbreviations are written inside of brackes `[]`. Also note that abbreviated units are case sensitive, while written out units are case insensitive (and the same is true for prefixes). TODO->write out all the unit conversion

#### Mass [M]
`[g]`, `gram`, `grams` (note that the base unit is `kg`/`kilograms`)  
`[lb]`, `[lbm]` `pound`, `pounds`, `pound-mass`, `pounds-mass`  
`slug`, `slugs`

#### Length [L]
`[m]`, `meter`, `meters`, `metre`, `metres`

#### Time [T]
`[s]` `second`, `seconds`

#### Electric Current [I]
`[A]`, `amp`, `amps`, `ampere`, `amperes`

#### Thermodynamic Temperature [Θ]
`[K]`, `kelvin` (note the plural of `kelvin` is `kelvin`)

#### Amount of Substance [N]
`[mol]`, `mole`, `moles`

#### Luminous Intensity [J]
`[cd]`, `candela`, `candelas`

### Named Derived Units

#### Plane Angle
`[rad]`, `radian`, `radians`

#### Solid Angle
`[sr]`, `steradian`, `steradian`, `steradians`

#### Frequency
`[Hz]`, `hertz`

#### Force / Weight
`[N]`, `newton`, `newtons`
`[lbf]`, `pound-force`, `pounds-force`

#### Pressure / Stress
`[Pa]`, `pascal`, `pascals`

#### Energy / Work / Heat
`[J]`, `joule`, `joules`

#### Power / Radiant Flux
`[W]`, `watt`, `watts`

#### Electric Charge / Quantity of Electricity
`[C]`, `coulomb`, `coulombs`

#### Voltage / Electrical Potential / EMF
`[V]`, `volt`, `volts`

#### Capacitance
`[F]`, `farad`, `farads`

#### Reistance / Impedance / Reactance
`[Ω]`, `ohm`, `ohms`

#### Electrical Conductance
`[S]`, `siemens`

#### Magnetic Flux
`[Wb]`, `weber`, `webers`

#### Magnetic Flux Density
`[T]`, `tesla`, `teslas`

#### Inductance
`[H]`, `henry`, `henries`, `henrys`

#### Relative Temperature
`[°C]`, `celsius`, `degrees-celsius`  
`[°F]`, `fahrenheit`, `degrees-fahrenheit`

#### Luminous Flux
`[lm]`, `lumen`, `lumens`

#### Illuminance
`[lx]`, `lux`, `luxes`

#### Radioactivity (Decays per unit time)
`[Bq]`, `becquerel`, `becquerels`

#### Absorbed Dose (of Ionizing Radiation)
`[Gy]`, `gray`, `grays`

#### Equivalent Dose (of Ionising Radiation)
`[Sv]`, `sievert`, `sieverts`

#### catalytic activity
`[kat]`, `katal`, `katals`

(TODO->all other units + weird units. e.g. drops)

### SI Prefixes
Note that SI prefixes only work for SI base and derived units (and a few exceptions noted below). 

Also note that the abbreviated forms of prefixes may only be combined with abbreviated units, and written out prefixes may only be combined with written out units. E.g. `kilograms` and `kg` are valid, but `kgrams` and `kilog` are invalid.

10^24 = `[Y]`, `yotta`  
10^21 = `[Z]`, `zetta`  
10^18 = `[E]`, `exa`   
10^15 = `[P]`, `peta`  
10^12 = `[T]`, `tera`  
10^9 = `[G]`, `giga`  
10^6 = `[M]`, `mega`  
10^3 = `[k]`, `kilo`  
10^2 = `[h]`, `hecto`  
10^1 = `[da]`, `deca`  
10^−1 = `[d]`, `deci`   
10^−2 = `[c]`, `centi`  
10^−3 = `[m]`, `milli`  
10^−6 = `[μ]`, `[u]`, `micro`  
10^−9 = `[n]`, `nano`  
10^−12 = `[p]`, `pico`  
10^−15 = `[f]`, `femto`  
10^−18 = `[a]`, `atto`  
10^−21 = `[z]`, `zepto`  
10^−24 = `[y]`, `yocto`  
# Changelog: world.opensemantic.characteristics.quantitative

Migration from SPARQL-based extraction to enriched QUDT JSON-LD (qudt-parsing).
QUDT version: 3.1.4

## Summary

| Metric | Old | New | Delta |
|--------|-----|-----|-------|
| Total characteristics | 934 | 934 | +0 |
| Removed | - | - | 0 |
| Added | - | - | 0 |
| Common | - | - | 934 |

## Known Limitations

- Some QUDT quantity kinds have no `applicableUnit` linked (e.g., BloodGlucoseLevel variants).
  These appear as removed characteristics with no replacement.
- Duplicate units exist in QUDT (e.g., `unit:FemtoM` and `unit:FEMTOM`) causing duplicate enum entries.

## Removed Characteristics

### Fundamental (0)


### Non-fundamental (0)


## Added Characteristics

### Fundamental (0)


### Non-fundamental (0)


## Hierarchy Changes

| Characteristic | Old Parent | New Parent |
|---------------|-----------|-----------|
| LinearAcceleration | `Category:OSW4082937906634af992cf9a1b18d772cf` | `Category:OSW347462e67d905995af16f97dc7c9ef48` |

## Unit Enumeration Changes

147 characteristics have changed unit enumerations.

| Characteristic | Old | New | Added Units | Removed Units |
|---------------|-----|-----|-------------|---------------|
| Unknown | 80 | 102 | /(mol·L), /(m·m·sr), /(m·nm·sr), /(μmol·L), A/(mol·L), Bq/(m²·d), K·m²/(g·s), K·m²/(kg·s), L/(m²·d), MHz·m, N·m²/g², N·m²/kg² (+39 more) | /(m·nm·sr), /(μmol·L), K·m²/(kg·s), MHz·m, N·m²/kg², cm²/cm³, kHz·m, kg/(m³·s) (+21 more) |
| EnergyCost | 11 | 19 | CHF/(W·h), CHF/(kW·h), Ft/(kW·h), Ft/Wh, Kč/(W·h), Kč/(kW·h), L/(kW·h), RON/(W·h), kr/(W·h), kr/(kW·h), zł/(W·h), zł/(kW·h) (+4 more) | CHF/(kW·h), Ft/(kW·h), Kč/(kW·h), L/(kW·h), kr/(kW·h), zł/(kW·h), £/(kW·h), лв./(kW·h) |
| CatalyticActivityConcentration | 16 | 20 | mkat/L, mmol/(m³·d), mol/(L·d), mol/(L·h), mol/(m³·d), mol/(m³·h), nkat/L, nmol/(L·d), nmol/(L·h), nmol/(cm³·h), pmol/(L·d), pmol/(L·h) (+1 more) | mkat/L, mmol/(m³·d), nkat/L, nmol/(L·d), nmol/(L·h), nmol/(cm³·h), pmol/(L·d), pmol/(L·h) (+1 more) |
| MassPerAreaTime | 16 | 20 | Mg/(ha·a), g/(ha·a), g/(m²·s), g/(m²·wk), g/(s·m²), kg/(ha·a), kg/(m²·s), kg/(s·m²), mg/(m²·s), μg/(cm²·wk) | Mg/(ha·a), kg/(ha·a), kg/(m²·s), kg/(s·m²), mg/(m²·s), μg/(cm²·wk) |
| LinearMomentum | 3 | 6 | g·cm/s, g·m/s, kg·cm/s, kg·m/s | kg·m/s |
| SpecificVolume | 8 | 11 | L/g, L/kg, cm³/g, dL/g, dm³/kg, mL/g, mL/kg, mm³/g, mm³/kg, m³/g, m³/kg | L/kg, cm³/g, dL/g, mL/g, mL/kg, mm³/g, mm³/kg, m³/kg |
| AbsorbedDoseRate | 8 | 11 | Sv/h, mSv/h, mW/mg, nSv/h, μSv/h | mW/mg, μSv/h |
| LengthMass | 2 | 5 | g·m, g·mm, kg·m, m·g, m·kg | g·mm, m·kg |
| SpecificPower | 8 | 11 | Sv/h, mSv/h, mW/mg, nSv/h, μSv/h | mW/mg, μSv/h |
| DynamicViscosity | 4 | 7 | g/(cm·s), g/(m·h), g/(m·s), kg/(m·h), kg/(m·s), mPa·s | kg/(m·h), kg/(m·s), mPa·s |
| MassicActivity | 4 | 7 | Bq/g, Bq/kg, MBq/kg, kBq/kg, mBq/g, mBq/kg, μBq/kg | Bq/kg, mBq/g, mBq/kg, μBq/kg |
| Impulse | 1 | 4 | g·cm/s, g·m/s, kg·cm/s, kg·m/s | kg·m/s |
| KermaRate | 5 | 8 | Sv/h, mSv/h, nSv/h, μSv/h | μSv/h |
| SpecificActivity | 4 | 7 | Bq/g, Bq/kg, MBq/kg, kBq/kg, mBq/g, mBq/kg, μBq/kg | Bq/kg, mBq/g, mBq/kg, μBq/kg |
| Viscosity | 4 | 7 | g/(cm·s), g/(m·h), g/(m·s), kg/(m·h), kg/(m·s), mPa·s | kg/(m·h), kg/(m·s), mPa·s |
| Momentum | 3 | 6 | g·cm/s, g·m/s, kg·cm/s, kg·m/s | kg·m/s |
| BurstFactor | 1 | 3 | Pa·m²/g, Pa·m²/kg, kPa·m²/g | kPa·m²/g |
| EnergyPerArea | 18 | 20 | GJ/m², MJ/m², erg/cm², erg/m², g/s², kW·h/m², kg/s² | GJ/m², MJ/m², erg/cm², kW·h/m², kg/s² |
| VolumetricFlux | 2 | 4 | L/(m²·min), L/(m²·s), mL/(cm²·min), mL/(cm²·s) | mL/(cm²·min), mL/(cm²·s) |
| AreaTime | 2 | 4 | cm²·min, cm²·s, m²·min, m²·s | cm²·min, cm²·s |
| MassPerArea | 18 | 20 | g/ft², g/in², kg/ft², kg/ha, μg/in² | kg/ft², kg/ha, μg/in² |
| MassSpecificBiogeochemicalRate | 4 | 6 | g/(g·d), g/(g·h), mg/(g·h), mg/(kg·d), μg/(g·d), μg/(g·h) | mg/(g·h), mg/(kg·d), μg/(g·d), μg/(g·h) |
| Unbalance | 1 | 3 | g·m, g·mm, kg·m | g·mm |
| MolarFluxDensity | 6 | 7 | mmol/(m²·h), mol/(m²·h), μmol/(m²·h) | mmol/(m²·h), μmol/(m²·h) |
| InverseEnergy | 1 | 2 | /(VA·h), /(kVA·h) | /(kVA·h) |
| ParticleFluence | 2 | 3 | /(m·nm), m^-2 | /(m·nm) |
| AngularMomentum | 5 | 6 | aJ·s, g·m²/s, kg·m²/s | aJ·s, kg·m²/s |
| ConductivityVariance | 1 | 2 | S²/m², μS²/cm² | μS²/cm² |
| AngularImpulse | 5 | 6 | aJ·s, g·m²/s, kg·m²/s | aJ·s, kg·m²/s |
| PowerPerElectricCharge | 3 | 4 | V/min, mV/min | mV/min |
| ElectricChargePerMass | 6 | 7 | C/g, C/kg, MHz/T, mC/kg | C/kg, MHz/T, mC/kg |
| SpecificModulus | 3 | 4 | GPa·cm³/g, Pa·m³/g, km²/s² | GPa·cm³/g, km²/s² |
| MomentOfInertia | 3 | 4 | g·m², kg·cm², kg·mm², kg·m² | kg·cm², kg·mm², kg·m² |
| ForcePerArea | 14 | 15 | g/(m·s²), kg/(m·s²) | kg/(m·s²) |
| WaterVapourDiffusionCoefficient | 1 | 2 | g/(Pa·s·m), kg/(Pa·s·m) | kg/(Pa·s·m) |
| MassConcentrationRateOfChange | 1 | 2 | g/(L·d), μg/(L·d) | μg/(L·d) |
| TorquePerAngle | 2 | 3 | N·m/°, kN·m/° | kN·m/° |
| LengthTemperatureTime | 1 | 2 | cm·s·°C, m·s·°C | cm·s·°C |
| PowerPerArea | 9 | 10 | J/(cm²·d), J/(m²·d), MJ/(m²·d) | J/(cm²·d), MJ/(m²·d) |
| CoefficientOfHeatTransfer | 3 | 4 | g/(s³·K), kg/(s³·K) | kg/(s³·K) |
| MassFlowRate | 21 | 22 | Mt/a, g/a, kg/a, kg/s, kt/a, mg/d, mg/s | Mt/a, kg/a, kg/s, kt/a, mg/d, mg/s |
| StressOpticCoefficient | 5 | 6 | m/(m·Pa), nm/(cm·MPa), nm/(mm·MPa) | nm/(cm·MPa), nm/(mm·MPa) |
| ParticleFluenceRate | 2 | 3 | m/(L·d), μm/(L·d) | μm/(L·d) |
| Flux | 3 | 4 | m/(L·d), μm/(L·d) | μm/(L·d) |
| MassTemperature | 1 | 2 | g·K, kg·K | kg·K |
| MolarMassVariationDueToPressure | 1 | 2 | mol/(g·Pa), mol/(kg·Pa) | mol/(kg·Pa) |
| SpecificHeatVolume | 1 | 2 | J/(g·K·m³), J/(kg·K·m³) | J/(kg·K·m³) |
| ExposureRate | 1 | 2 | C/(g·s), C/(kg·s) | C/(kg·s) |
| SpecificOpticalRotatoryPower | 1 | 2 | rad·m²/g, rad·m²/kg | rad·m²/kg |
| PhotosyntheticPhotonFluxDensity | 11 | 12 | mmol/(m²·d), mmol/(m²·h), mol/(m²·h), μmol/(m²·d), μmol/(m²·h) | mmol/(m²·d), mmol/(m²·h), μmol/(m²·d), μmol/(m²·h) |
| PressureLossPerLength | 1 | 2 | g/(m²·s²), kg/(m²·s²) | kg/(m²·s²) |
| SpecificEnergy | 6 | 7 | N·m/g, N·m/kg | N·m/kg |
| VolumetricHeatCapacity | 3 | 4 | cal/(cm³·K), cal_th/(m³·K) | cal/(cm³·K) |
| SurfaceDensity | 12 | 13 | g/in², μg/in² | μg/in² |
| Power | 33 | 34 | GJ/h, MJ/h, MJ/s, MPa·L/s, TW·h/a, W·h/a | GJ/h, MJ/h, MJ/s, MPa·L/s, TW·h/a |
| IonicStrength | 11 | 12 | cmol/kg, fmol/kg, kmol/kg, mmol/g, mmol/kg, mol/g, mol/kg, nmol/g, nmol/kg, pmol/kg, μmol/g, μmol/kg | cmol/kg, fmol/kg, kmol/kg, mmol/g, mmol/kg, mol/kg, nmol/g, nmol/kg (+3 more) |
| TotalMassStoppingPower | 1 | 2 | J·m²/g, J·m²/kg | J·m²/kg |
| VapourPermeance | 3 | 4 | g/(m^2·Pa·s), kg/(m²·Pa·s), ng/(m²·Pa·s) | kg/(m²·Pa·s), ng/(m²·Pa·s) |
| TorsionalSpringConstant | 2 | 3 | N·m/°, kN·m/° | kN·m/° |
| InverseSquareMass | 1 | 2 | /g², /kg² | /kg² |
| LinearCompressibility | 1 | 2 | m/N, μm/N | μm/N |
| LengthTemperature | 3 | 4 | °C·cm, °C·m | °C·cm |
| CostPerMass | 1 | 2 | CHF/g, CHF/kg | CHF/kg |
| MassPerEnergy | 2 | 3 | g/J, kg/GJ, kg/J | kg/GJ, kg/J |
| RotationalMass | 3 | 4 | g·m², kg·cm², kg·mm², kg·m² | kg·cm², kg·mm², kg·m² |
| LengthEnergy | 1 | 2 | MeV·fm, eV·m | MeV·fm |
| AmountOfSubstancePerMass | 11 | 12 | cmol/kg, fmol/kg, kmol/kg, mmol/g, mmol/kg, mol/g, mol/kg, nmol/g, nmol/kg, pmol/kg, μmol/g, μmol/kg | cmol/kg, fmol/kg, kmol/kg, mmol/g, mmol/kg, mol/kg, nmol/g, nmol/kg (+3 more) |
| SpecificHeatPressure | 1 | 2 | J/(g·K·Pa), J/(kg·K·Pa) | J/(kg·K·Pa) |
| VapourPermeability | 1 | 2 | g/(Pa·s·m), kg/(Pa·s·m) | kg/(Pa·s·m) |
| VolumePerTime | 22 | 22 | cm³/d, cm³/h, cm³/min, cm³/s, dm³/h, dm³/min, dm³/s, kL/h, mL/d, mL/h, mL/s | cm³/d, cm³/h, cm³/min, cm³/s, dm³/h, dm³/min, dm³/s, kL/h (+3 more) |
| ElectromagneticWavePhaseSpeed | 8 | 8 | cm/s, km/s, mm/min, mm/s, μm/min, μm/s | cm/s, km/s, mm/min, mm/s, μm/min, μm/s |
| BloodGlucoseLevel | 7 | 7 | cmol/L, fmol/L, nmol/L, pmol/L, μmol/L | cmol/L, fmol/L, nmol/L, pmol/L, μmol/L |
| Permeability | 3 | 3 | nH/m, μH/m | nH/m, μH/m |
| RadiantEnergyDensity | 2 | 2 | MJ/m³ | MJ/m³ |
| TorquePerLength | 2 | 2 | kN·m/m | kN·m/m |
| HydraulicPermeability | 9 | 9 | cm², dm², mm², nm², μm² | cm², dm², mm², nm², μm² |
| DiffusionCoefficient | 3 | 3 | cm²/s, mm²/s | cm²/s, mm²/s |
| LineicMass | 7 | 7 | mg/m | mg/m |
| Area | 10 | 10 | cm², dm², mm², nm², μm² | cm², dm², mm², nm², μm² |
| Speed | 13 | 13 | MHz·m, cm/s, kHz·m, km/s, mm/min, mm/s, μm/min, μm/s | MHz·m, cm/s, kHz·m, km/s, mm/min, mm/s, μm/min, μm/s |
| MeasurementUnitOfSpectralRadiance | 10 | 10 | mW/(cm²·μm·sr) | mW/(cm²·μm·sr) |
| MomentOfForce | 8 | 8 | MN·m, dN·m, mN·m | MN·m, dN·m, mN·m |
| Acceleration | 4 | 4 | cm/s² | cm/s² |
| Velocity | 24 | 24 | MHz·m, cm/a, cm/ka, cm/s, kHz·m, km/d, km/s, mm/a, mm/min, mm/s, μm/min, μm/s | MHz·m, cm/a, cm/ka, cm/s, kHz·m, km/d, km/s, mm/a (+4 more) |
| Permeability | 3 | 3 | nH/m, μH/m | nH/m, μH/m |
| BloodGlucoseLevelByMass | 17 | 17 | fg/L, mg/L, mg/dL, ng/L, ng/dL, ng/mL, ng/μL, pg/L, pg/mL, μg/mL | fg/L, mg/L, mg/dL, ng/L, ng/dL, ng/mL, ng/μL, pg/L (+2 more) |
| Conductivity | 12 | 12 | nS/cm | nS/cm |
| DisplacementCurrentDensity | 5 | 5 | MA/m² | MA/m² |
| ElectrolyticConductivity | 12 | 12 | nS/cm | nS/cm |
| Concentration | 12 | 12 | cmol/L, fmol/L, kmol/m³, mmol/m³, nmol/L, pmol/L, μmol/L | cmol/L, fmol/L, kmol/m³, mmol/m³, nmol/L, pmol/L, μmol/L |
| SoundVolumeVelocity | 3 | 3 | cm³/s, dm³/s | cm³/s, dm³/s |
| MassDensity | 29 | 29 | fg/L, mg/L, mg/dL, ng/L, ng/dL, ng/mL, ng/μL, pg/L, pg/mL, μg/mL | fg/L, mg/L, mg/dL, ng/L, ng/dL, ng/mL, ng/μL, pg/L (+2 more) |
| RecombinationCoefficient | 3 | 3 | cm³/s, dm³/s | cm³/s, dm³/s |
| Density | 29 | 29 | fg/L, mg/L, mg/dL, ng/L, ng/dL, ng/mL, ng/μL, pg/L, pg/mL, μg/mL | fg/L, mg/L, mg/dL, ng/L, ng/dL, ng/mL, ng/μL, pg/L (+2 more) |
| ForcePerAreaTime | 4 | 4 | hPa/h | hPa/h |
| SecondAxialMomentOfArea | 3 | 3 | cm⁴, mm⁴ | cm⁴, mm⁴ |
| SectionModulus | 6 | 6 | cm³, dam³, dm³, mm³, μm³ | cm³, dam³, dm³, mm³, μm³ |
| AreaPerTime | 5 | 5 | cm²/s, mm²/s | cm²/s, mm²/s |
| Action | 2 | 2 | aJ·s | aJ·s |
| PressureGradient | 6 | 6 | kPa/mm, pPa/km | kPa/mm, pPa/km |
| Torque | 8 | 8 | MN·m, dN·m, mN·m | MN·m, dN·m, mN·m |
| NuclearQuadrupoleMoment | 7 | 7 | cm², dm², mm², nm², μm² | cm², dm², mm², nm², μm² |
| MolarVolume | 5 | 5 | cm³/mol | cm³/mol |
| ActivityConcentration | 5 | 5 | mBq/L, nBq/L, μBq/L | mBq/L, nBq/L, μBq/L |
| MassConcentration | 27 | 27 | fg/L, mg/L, mg/dL, ng/L, ng/dL, ng/mL, ng/μL, pg/L, pg/mL, μg/mL | fg/L, mg/L, mg/dL, ng/L, ng/dL, ng/mL, ng/μL, pg/L (+2 more) |
| SecondPolarMomentOfArea | 3 | 3 | cm⁴, mm⁴ | cm⁴, mm⁴ |
| RadiantFluence | 5 | 5 | GJ/m², MJ/m² | GJ/m², MJ/m² |
| StandardGravitationalParameter | 2 | 2 | km³/s² | km³/s² |
| DiffusionCoefficient | 3 | 3 | cm²/s, mm²/s | cm²/s, mm²/s |
| LinearVelocity | 24 | 24 | MHz·m, cm/a, cm/ka, cm/s, kHz·m, km/d, km/s, mm/a, mm/min, mm/s, μm/min, μm/s | MHz·m, cm/a, cm/ka, cm/s, kHz·m, km/d, km/s, mm/a (+4 more) |
| PressureCoefficient | 4 | 4 | MPa/K | MPa/K |
| Permittivity | 6 | 6 | nF/m, pF/m, μF/km, μF/m | nF/m, pF/m, μF/km, μF/m |
| EnergyDensity | 3 | 3 | MJ/m³ | MJ/m³ |
| Mobility | 2 | 2 | cm²/(V·s) | cm²/(V·s) |
| ElectricCurrentDensity | 5 | 5 | MA/m² | MA/m² |
| MassPerTime | 14 | 14 | Mt/a, kg/s, kt/a, mg/d, mg/s | Mt/a, kg/s, kt/a, mg/d, mg/s |
| ElectricCharge | 27 | 27 | kA·h, mA·h | kA·h, mA·h |
| SecondMomentOfArea | 3 | 3 | cm⁴, mm⁴ | cm⁴, mm⁴ |
| SpecificAcousticImpedance | 2 | 2 | kg/(m²·s) | kg/(m²·s) |
| EnergyPerTemperature | 3 | 3 | kJ/K | kJ/K |
| MassPerLength | 7 | 7 | mg/m | mg/m |
| Energy | 27 | 27 | MVA·h, kVA·h | MVA·h, kVA·h |
| Entropy | 3 | 3 | kJ/K | kJ/K |
| ElectricConductivity | 13 | 13 | nS/cm | nS/cm |
| TotalCurrentDensity | 5 | 5 | MA/m² | MA/m² |
| VolumicElectromagneticEnergy | 2 | 2 | MJ/m³ | MJ/m³ |
| ElectricChargeDensity | 8 | 8 | GC/m³, MC/m³, kC/m³, mC/m³, μC/m³ | GC/m³, MC/m³, kC/m³, mC/m³, μC/m³ |
| ElectromagneticEnergyDensity | 2 | 2 | MJ/m³ | MJ/m³ |
| TotalLinearStoppingPower | 4 | 4 | MeV/cm, keV/μm | MeV/cm, keV/μm |
| LinearEnergyTransfer | 4 | 4 | MeV/cm, keV/μm | MeV/cm, keV/μm |
| ThermalDiffusionCoefficient | 3 | 3 | cm²/s, mm²/s | cm²/s, mm²/s |
| ReactionRateConstant | 2 | 2 | cm³/(mol·s) | cm³/(mol·s) |
| ElectricChargeVolumeDensity | 8 | 8 | GC/m³, MC/m³, kC/m³, mC/m³, μC/m³ | GC/m³, MC/m³, kC/m³, mC/m³, μC/m³ |
| EnergyFluence | 5 | 5 | GJ/m², MJ/m² | GJ/m², MJ/m² |
| Volume | 18 | 18 | cm³, dam³, dm³, mm³, μm³ | cm³, dam³, dm³, mm³, μm³ |
| MolarRefractivity | 5 | 5 | cm³/mol | cm³/mol |
| VolumeFlowRate | 22 | 22 | cm³/d, cm³/h, cm³/min, cm³/s, dm³/h, dm³/min, dm³/s, kL/h, mL/d, mL/h, mL/s | cm³/d, cm³/h, cm³/min, cm³/s, dm³/h, dm³/min, dm³/s, kL/h (+3 more) |
| VolumeThermalExpansion | 4 | 4 | mL/K | mL/K |
| BatteryCapacity | 5 | 5 | kA·h, mA·h | kA·h, mA·h |
| LinearDensity | 7 | 7 | mg/m | mg/m |
| MassRatio | 15 | 15 | mg/g, ng/kg, μg/g, μg/kg | mg/g, ng/kg, μg/g, μg/kg |
| SoundExposureLevel | 3 | 2 |  | dBmW |
| RotationalFrequency | 11 | 10 |  | c/s |
| Mass | 17 | 16 |  | AT |
| LinearAcceleration | 4 | 0 |  | cm/s², km/s², m/s², mm/s² |
| SpectralRadiantEnergyDensity | 7 | 1 |  | Pa/m, hPa/m, kPa/m, kPa/mm, mPa/m, pPa/km |
| ForcePerLength | 13 | 5 | mN/m | GN·m/m², MN·m/m², N·m/m², cN·m/m², kN·m/m², mN/m, mN·m/m², nN·m/m² (+1 more) |


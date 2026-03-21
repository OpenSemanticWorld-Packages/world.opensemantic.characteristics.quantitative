# Changelog: world.opensemantic.characteristics.quantitative

Migration from SPARQL-based extraction to enriched QUDT JSON-LD (qudt-parsing).
QUDT version: 3.1.4

## Summary

| Metric | Old | New | Delta |
|--------|-----|-----|-------|
| Total characteristics | 825 | 934 | +109 |
| Removed | - | - | 25 |
| Added | - | - | 134 |
| Common | - | - | 800 |

## Known Limitations

- Some QUDT quantity kinds have no `applicableUnit` linked (e.g., BloodGlucoseLevel variants).
  These appear as removed characteristics with no replacement.
- Duplicate units exist in QUDT (e.g., `unit:FemtoM` and `unit:FEMTOM`) causing duplicate enum entries.

## Removed Characteristics

### Fundamental (14)

| Name | Units | Unit Symbols |
|------|-------|-------------|
| BloodGlucoseLevelByMass | 10 | g/L, mg/mL, g/mL, fg/L, pg/L, kg/L, μg/L, ng/L, g/dL, mg/L |
| CubicElectricDipoleMomentPerSquareEnergy | 1 | C³·m/J² |
| EnergyPerSquareMagneticFluxDensity | 1 | J/T² |
| InverseSquareEnergy | 1 | 1/J² |
| InverseSquareMass | 1 | 1/kg² |
| InverseSquareTime | 1 | 1/s² |
| LineicPower | 1 | W/m |
| NeonConductivityVariance | 1 | uS2/cm2 |
| NeonTemperatureVariance | 1 | °C² |
| QuarticElectricDipoleMomentPerCubicEnergy | 1 | C⁴·m⁴/J³ |
| TemperaturePerTimeSquared | 1 | K/s² |
| TimeSquared | 1 | s² |
| VaporPermeability | 1 | kg/(Pa·s·m) |
| VaporPermeance | 1 | kg/(m²·Pa·s) |

### Non-fundamental (11)

| Name | Parent |
|------|--------|
| ActivityRelatedByMass | `Category:OSW9cb88f0c339451c59ecf9587128ee4b5` |
| AreicEnergyFlow | `Category:OSW40c46aba16f45962a7330b7f8b88681e` |
| AreicMass | `Category:OSWb9612bfb909c5eab9e57e8d8a6c86082` |
| AtomicEnergy | `Category:OSWc87ddd4a7d1159f0a75b686a61ef4e8e` |
| ByteDataVolume | `Category:OSWb0250d3677f6592f9d4329c8b9d5f8d1` |
| CharacteristicNumber | `Category:OSWbcaa33bd770e53e09d5e6087d141648b` |
| KineticOrThermalEnergy | `Category:OSWc87ddd4a7d1159f0a75b686a61ef4e8e` |
| LuminousExitance | `Category:OSW79225fde5f8059d1802f8181c06b4cfa` |
| MechanicalTension | `Category:OSW2ff3a26daf13563481acc8b0ebc5b37f` |
| MolarThermodynamicEnergy | `Category:OSW21ec5968e3c2533d98f20564838541fa` |
| NeutralRatio | `Category:OSW67faac860ed758758aa4484387e5d5c9` |

## Added Characteristics

### Fundamental (100)

| Name | Units | Unit Symbols |
|------|-------|-------------|
| Absorptance | 1 | 一 |
| ActivityCoefficient | 1 | 一 |
| AtomScatteringFactor | 1 | 一 |
| AverageLogarithmicEnergyDecrement | 1 | 一 |
| BindingFraction | 1 | 一 |
| BloodGlucoseLevelByMass | 17 | g/L, fg/L, pg/L, ng/L, pg/mL, ng/dL, ng/mL, μg/L, μg/dL, mg/L |
| BurstFactor | 1 | kPa·m²/g |
| CanonicalPartitionFunction | 1 | 一 |
| Chromaticity | 1 | 一 |
| ConductivityVariance | 1 | μS²/cm² |
| CostPerArea | 2 | €/m², CHF/ha |
| CostPerMass | 1 | CHF/kg |
| CostPerPower | 2 | €/W, €/kW |
| CouplingFactor | 1 | 一 |
| CubicElectricDipoleMomentPerSquareEnergy | 1 | C³·m/J² |
| DatasetOfBits | 13 | b, kb, Kib, Mb, Mib, Gb, Gib, Tb, Tib, Pib |
| DebyeWallerFactor | 1 | 一 |
| DegreeOfDissociation | 1 | 一 |
| DeltaUV | 1 | 一 |
| Dissipance | 1 | 一 |
| DoseEquivalentQualityFactor | 1 | 一 |
| EinsteinTransitionProbability | 1 | 一 |
| ElectricConductivity | 13 | S/m, pS/m, stat℧, nS/m, nS/cm, μS/m, μS/cm, mS/m, dS/m, mS/cm |
| ElectricSusceptibility | 1 | 一 |
| ElectricalConductance | 8 | S, pS, nS, μS, mS, dS, kS, MS |
| EnergyCost | 11 | €/(W·s), CHF/(kW·h), Ft/(kW·h), Kč/(kW·h), L/(kW·h), kr/(kW·h), zł/(kW·h), £/(kW·h), лв./(kW·h), €/(kW·h) |
| EnergyPerSquareMagneticFluxDensity | 1 | J/T² |
| EquilibriumConstant | 1 | 一 |
| FastFissionFactor | 1 | 一 |
| Fluidity | 1 | /(Pa·s) |
| FractionalAmountOfSubstance | 7 | #, ppq, ppt, PPB, PPTM, PPM, ‰ |
| GFactorOfNucleus | 1 | 一 |
| GeneralizedCoordinate | 1 | 一 |
| GeneralizedForce | 1 | 一 |
| GeneralizedForce | 1 | 一 |
| GeneralizedVelocity | 1 | 一 |
| GruneisenParameter | 1 | 一 |
| Impulse | 1 | kg·m/s |
| InternalConversionFactor | 1 | 一 |
| InverseSquareEnergy | 3 | /J², /GeV², /eV² |
| InverseSquareMass | 1 | /kg² |
| InverseSquareTime | 1 | /s² |
| IsentropicExponent | 1 | 一 |
| LandeGFactor | 1 | 一 |
| LeakageFactor | 1 | 一 |
| Lethargy | 1 | 一 |
| LineicMass | 7 | kg/m, g/km, mg/m, g/m, kg/km, g/mm, kg/mm |
| LogarithmicFrequencyInterval | 2 | 一, octave |
| LongRangeOrderParameter | 1 | 一 |
| LossFactor | 1 | 一 |
| MadelungConstant | 1 | 一 |
| MagneticSusceptability | 1 | 一 |
| MassConcentrationOfWaterToDryMatter | 1 | 一 |
| MassFraction | 1 | 一 |
| MassFractionOfDryMatter | 1 | 一 |
| MassFractionOfWater | 1 | 一 |
| MassRatioOfWaterVapourToDryGas | 1 | 一 |
| MobilityRatio | 1 | 一 |
| MultiplicationFactor | 1 | 一 |
| NapierianAbsorbance | 1 | 一 |
| NeutronYieldPerAbsorption | 1 | 一 |
| NeutronYieldPerFission | 1 | 一 |
| NonLeakageProbability | 1 | 一 |
| NumberOfParticles | 1 | 一 |
| OrderOfReflection | 1 | 一 |
| OsmoticCoefficient | 1 | 一 |
| PackingFraction | 1 | 一 |
| PermeabilityRatio | 1 | # |
| PoissonRatio | 1 | 一 |
| PowerFactor | 1 | 一 |
| PressureGradient | 6 | Pa/m, pPa/km, mPa/m, hPa/m, kPa/m, kPa/mm |
| QualityFactor | 1 | 一 |
| QuarticElectricDipoleMomentPerCubicEnergy | 1 | C⁴·m⁴/J³ |
| RadianceFactor | 1 | 一 |
| RatioOfSpecificHeatCapacities | 1 | 一 |
| Reactivity | 1 | 一 |
| ReflectanceFactor | 1 | 一 |
| RefractiveIndex | 1 | 一 |
| RelativeMassConcentrationOfVapour | 1 | 一 |
| RelativeMassDensity | 1 | 一 |
| RelativeMassExcess | 1 | 一 |
| RelativeMassRatioOfVapour | 1 | 一 |
| ResonanceEscapeProbability | 1 | 一 |
| ShortRangeOrderParameter | 1 | 一 |
| SignalDetectionThreshold | 1 | dBc |
| SquareTime | 1 | s² |
| StandardAbsoluteActivity | 1 | 一 |
| StatisticalWeight | 1 | 一 |
| StressIntensityFactor | 2 | Pa√m, MPa√m |
| StructureFactor | 1 | 一 |
| TemperaturePerSquareTime | 1 | K/s² |
| TemperatureVariance | 1 | °C² |
| ThermalDiffusionFactor | 1 | 一 |
| ThermalDiffusionRatio | 1 | 一 |
| ThermalUtilizationFactor | 1 | 一 |
| TotalIonization | 1 | 一 |
| TransmittanceDensity | 1 | 一 |
| Unbalance | 1 | g·mm |
| VapourPermeability | 1 | kg/(Pa·s·m) |
| VapourPermeance | 3 | s/m, ng/(m²·Pa·s), kg/(m²·Pa·s) |

### Non-fundamental (34)

| Name | Parent |
|------|--------|
| ApiGravity | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| ApiGravity | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| BioconcentrationFactor | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| ConductiveHeatTransferRate | `Category:OSW2cae7f47264e5a25abee5713c593bc56` |
| Constringence | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| ConvectiveHeatTransfer | `Category:OSW2cae7f47264e5a25abee5713c593bc56` |
| CurrencyPerFlight | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| Curvature | `Category:OSW23837e2c50f05ba884682b08465bf173` |
| Distance | `Category:OSWee9c7e5c343e542cb5a8b4648315902f` |
| DistanceTraveledDuringABurn | `Category:OSW5074a29ba5505fc98e379b0a9df0bd69` |
| DryVolume | `Category:OSWf5c54cd70ddf5ff3b1ef1aee6ae8f0cb` |
| EffectiveMultiplicationFactor | `Category:OSW4384c6d9e96657c0b4e77f665495be59` |
| EquilibriumConstantOnConcentrationBasis | `Category:OSWb7d41b44919f53239bac585d326e7933` |
| EquilibriumConstantOnPressureBasis | `Category:OSWb7d41b44919f53239bac585d326e7933` |
| GrandCanonicalPartitionFunction | `Category:OSWbb31e94e7ec453588382368a9a40c134` |
| GrowingDegreeDaysCereals | `Category:OSW6f81fb79192f50e280ee1ff5dd724f01` |
| HeatFlowRate | `Category:OSWa819b53101b854ad923f9f13dfb41794` |
| ImaginaryPartOfComplexFrequency | `Category:OSWc543ebb853385a1a9382f57faad6170d` |
| InfiniteMultiplicationFactor | `Category:OSW4384c6d9e96657c0b4e77f665495be59` |
| LogarithmOfOctanolWaterPartitionCoefficient | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| MachNumber | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| MagneticFieldStrength | `Category:OSW8ba7ac8b06c453e2885cc41c9d9ee0bb` |
| MassEquivalent | `Category:OSWe9be062de2d15d10891397a18212f920` |
| MicroCanonicalPartitionFunction | `Category:OSWbb31e94e7ec453588382368a9a40c134` |
| MolarEquivalent | `Category:OSW2f222621d774517193dc5eab674e3721` |
| MolecularMass | `Category:OSWe9be062de2d15d10891397a18212f920` |
| MomentOfInertiaInTheYAxis | `Category:OSW2e958a0e653558a8abf2bd1fa3c6dd59` |
| MomentOfInertiaInTheZAxis | `Category:OSW2e958a0e653558a8abf2bd1fa3c6dd59` |
| OctanolAirPartitionCoefficient | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| PermittivityRatio | `Category:OSW67faac860ed758758aa4484387e5d5c9` |
| RadiativeHeatTransfer | `Category:OSW2cae7f47264e5a25abee5713c593bc56` |
| SerumOrPlasmaLevel | `Category:OSW98493d0d7b8b528fa42a2332c8cf502f` |
| Turns | `Category:OSWb0250d3677f6592f9d4329c8b9d5f8d1` |
| WaterSolubility | `Category:OSW98493d0d7b8b528fa42a2332c8cf502f` |

## Hierarchy Changes

| Characteristic | Old Parent | New Parent |
|---------------|-----------|-----------|
| AuxillaryMagneticField | `Category:OSW5066212adfda5519af307363bd1c5c79` | `Category:OSW129f1aed78505813a671e17140ddd9e3` |
| SignalStrength | `Category:OSWc66c35bcf6bd5b08a2e9763d78a082cb` | `Category:OSW4f0b3f4a40ad5ffbb492a000abe2b30d` |
| CO2Equivalent | `Category:OSWea12214400965c818daf0b53062ccf4a` | `Category:OSW2f43065573625d76b8e242414ee4bedf` |
| AngularAcceleration | `Category:OSW3484a41e5b0e57f7998a5033177ab080` | `Category:OSWd33f5020bd93583b807f360af0e833ca` |

## Unit Enumeration Changes

227 characteristics have changed unit enumerations.

| Characteristic | Old | New | Added Units | Removed Units |
|---------------|-----|-----|-------------|---------------|
| Unknown | 1 | 80 | #, /(Pa·s), /(m·nm·sr), /(m·s), /(m·sr), /(μmol·L), /sr, GHz·m, Hz·m, K², K·Pa/s, K·m/s (+67 more) |  |
| ElectricCharge | 1 | 27 | A·h, C, EC, GC, MC, PC, TC, YC, ZC, aC, cC, dC (+14 more) |  |
| Power | 9 | 33 | EJ/s, EW, GJ/h, GJ/s, J/h, J/s, MJ/h, MJ/s, MPa·L/s, MPa·m³/s, PJ/s, PW (+12 more) |  |
| Time | 9 | 29 | H/kΩ, H/Ω, Ma, Ms, a, a{sidereal}, a{tropical}, d, day{sidereal}, h, h{sidereal}, ka (+8 more) |  |
| SpecificImpulseByWeight | 9 | 29 | H/kΩ, H/Ω, Ma, Ms, a, a{sidereal}, a{tropical}, d, day{sidereal}, h, h{sidereal}, ka (+8 more) |  |
| MassFlowRate | 1 | 21 | Mt/a, g/d, g/h, g/min, g/s, kg/a, kg/d, kg/h, kg/min, kg/s, kt/a, mg/d (+9 more) | kg/s |
| VolumePerTime | 3 | 22 | L/d, L/h, L/min, L/s, cm³/d, cm³/h, cm³/min, cm³/s, dm³/d, dm³/h, dm³/min, dm³/s (+9 more) | cm³/s, dm³/s |
| Velocity | 5 | 24 | GHz·m, Hz·m, MHz·km, MHz·m, cm/a, cm/h, cm/ka, cm/s, kHz·m, km/d, km/h, km/s (+11 more) | cm/s, km/s, mm/s, μm/s |
| MassDensity | 10 | 29 | Mg/m³, fg/L, g/cm³, g/dm³, g/m³, gr{UK}/m³, kg/cm³, kg/dm³, kg/m³, mg/L, mg/dL, mg/m³ (+11 more) | fg/L, mg/L, ng/L, pg/L |
| Density | 10 | 29 | Mg/m³, fg/L, g/cm³, g/dm³, g/m³, gr{UK}/m³, kg/cm³, kg/dm³, kg/m³, mg/L, mg/dL, mg/m³ (+11 more) | fg/L, mg/L, ng/L, pg/L |
| LinearVelocity | 5 | 24 | GHz·m, Hz·m, MHz·km, MHz·m, cm/a, cm/h, cm/ka, cm/s, kHz·m, km/d, km/h, km/s (+11 more) | cm/s, km/s, mm/s, μm/s |
| Frequency | 5 | 24 | /a, /d, /h, /min, /mo, /ms, /s, /wk, Bq, GBq, MBq, PBq (+7 more) |  |
| VolumeFlowRate | 3 | 22 | L/d, L/h, L/min, L/s, cm³/d, cm³/h, cm³/min, cm³/s, dm³/d, dm³/h, dm³/min, dm³/s (+9 more) | cm³/s, dm³/s |
| MassConcentration | 10 | 27 | Mg/m³, fg/L, g/cm³, g/dm³, g/m³, kg/cm³, kg/dm³, kg/m³, mg/L, mg/dL, mg/m³, ng/L (+9 more) | fg/L, mg/L, ng/L, pg/L |
| MassPerArea | 1 | 18 | Mg/ha, g/cm², g/ha, g/mm², g/m², kg/cm², kg/ft², kg/ha, kg/km², mg/cm², mg/dm², mg/ha (+5 more) |  |
| Energy | 10 | 27 | GW·h, GeV, Ha, MVA·h, MW·h, MeV, TW·h, VA·h, W·h, W·s, eV, kVA·h (+5 more) |  |
| Mass | 1 | 17 | AT, Mg, Mt, cg, dag, dg, dt, fg, g, hg, kt, mg (+4 more) |  |
| CatalyticActivityConcentration | 1 | 16 | kat/L, kat/μL, mkat/L, mmol/(m³·d), mol/(m³·s), nkat/L, nmol/(L·d), nmol/(L·h), nmol/(cm³·h), pkat/L, pmol/(L·d), pmol/(L·h) (+3 more) |  |
| EnergyPerArea | 5 | 18 | GJ/m², GN·m/m², J/cm², MJ/m², MN·m/m², N·m/m², W·h/m², W·s/m², cN·m/m², erg/cm², kN·m/m², kW·h/m² (+4 more) | GJ/m², J/cm², MJ/m² |
| MassPerAreaTime | 3 | 16 | Mg/(ha·a), g/(cm²·a), g/(m²·a), g/(m²·h), kg/(ha·a), kg/(m²·d), kg/(m²·s), kg/(s·m²), mg/(m²·h), mg/(m²·s), ng/(cm²·d), t/(ha·a) (+1 more) |  |
| MassPerTime | 1 | 14 | Mt/a, g/d, g/h, g/s, kg/d, kg/h, kg/s, kt/a, mg/d, mg/h, mg/s, ng/d (+1 more) |  |
| ForcePerLength | 1 | 13 | GN·m/m², MN·m/m², N/cm, N/m, N/mm, cN·m/m², kN/m, kN·m/m², mN/m, mN·m/m², nN·m/m², μN·m/m² |  |
| Volume | 6 | 18 | L, ML, cL, cm³, dL, daL, dam³, dm³, fL, hL, kL, mL (+5 more) | cm³, dam³, dm³, mm³, μm³ |
| AngularFrequency | 1 | 12 | Bq, GBq, MBq, PBq, TBq, kBq, mBq, nBq, rad/h, rad/min, μBq |  |
| SurfaceDensity | 1 | 12 | g/cm², g/mm², g/m², kg/cm², kg/km², mg/cm², mg/dm², mg/m², ng/cm², μg/cm², μg/in² |  |
| AngularVelocity | 1 | 12 | Bq, GBq, MBq, PBq, TBq, kBq, mBq, nBq, rad/h, rad/min, μBq |  |
| Resistivity | 1 | 11 | GΩ·m, MΩ·km, MΩ·m, kΩ·m, mΩ·m, nΩ·m, Ω·cm, Ω·km, Ω·m²/m, μΩ·m |  |
| BodyMassIndex | 1 | 11 | g/cm², g/mm², g/m², kg/cm², kg/km², mg/cm², mg/dm², mg/m², ng/cm², μg/cm² |  |
| Dimensionless | 1 | 11 | COUNT, Gbp, Np, bp, dec, flight, heartbeat, octave, χ, 一 |  |
| MeanMassRange | 1 | 11 | g/cm², g/mm², g/m², kg/cm², kg/km², mg/cm², mg/dm², mg/m², ng/cm², μg/cm² |  |
| Speed | 4 | 13 | MHz·km, MHz·m, cm/s, kHz·m, km/s, m/min, m/s, mm/min, mm/s, μm/min, μm/s | kHz·m, m·MHz |
| MassConcentrationOfWaterVapour | 1 | 10 | Mg/m³, g/cm³, g/m³, kg/cm³, kg/dm³, kg/m³, mg/m³, ng/m³, μg/m³ |  |
| ResidualResistivity | 1 | 10 | GΩ·m, MΩ·km, MΩ·m, kΩ·m, mΩ·m, nΩ·m, Ω·cm, Ω·km, μΩ·m |  |
| MassConcentrationOfWater | 1 | 10 | Mg/m³, g/cm³, g/m³, kg/cm³, kg/dm³, kg/m³, mg/m³, ng/m³, μg/m³ |  |
| MassRatio | 6 | 15 | fg/kg, g/hg, mg/g, mg/kg, ng/kg, ng/mg, pg/kg, pg/mg, μg/g, μg/kg, μg/mg | mg/g, μg/g |
| ElectricChargePerMass | 1 | 9 | /(T·s), C/kg, Hz/T, MHz/T, R, kR, mC/kg, mR |  |
| MeasurementUnitOfSpectralRadiance | 2 | 10 | W/(m²·m), W/(m²·nm), W/(m²·nm·sr), W/(m²·μm), W/(m²·μm·sr), mW/(cm²·μm·sr), mW/(m²·nm), mW/(m²·nm·sr), μW/(cm²·μm·sr) | W/(m²·nm·sr) |
| ForcePerAreaTime | 1 | 9 | Pa/h, Pa/min, W/(m²·m), W/(m²·nm), W/(m²·μm), W/m³, hPa/h, mW/(m²·nm) |  |
| PhotosyntheticPhotonFluxDensity | 3 | 11 | mmol/(m²·d), mmol/(m²·h), mol/(m²·d), nmol/(m²·d), nmol/(m²·s), pmol/(m²·d), μmol/(m²·d), μmol/(m²·h) |  |
| Voltage | 5 | 12 | EV, GV, PV, TV, fV, nV, pV |  |
| AbsorbedDoseRate | 1 | 8 | W/g, W/kg, mGy/s, mW/mg, nGy/s, μGy/s, μSv/h |  |
| Concentration | 5 | 12 | cmol/L, fmol/L, kmol/m³, mmol/L, mmol/m³, mol/L, mol/dm³, nmol/L, pmol/L, μmol/L | kmol/m³, mmol/m³, mol/dm³ |
| SpecificPower | 1 | 8 | W/g, W/kg, mGy/s, mW/mg, nGy/s, μGy/s, μSv/h |  |
| ElectricPotentialDifference | 5 | 12 | EV, GV, PV, TV, fV, nV, pV |  |
| MagnetomotiveForce | 6 | 13 | AT, GA, PA, TA, aA, fA, nA |  |
| EnergyPerElectricCharge | 5 | 12 | EV, GV, PV, TV, fV, nV, pV |  |
| ElectricPotential | 5 | 12 | EV, GV, PV, TV, fV, nV, pV |  |
| ElectricCurrentPhasor | 6 | 12 | GA, PA, TA, aA, fA, nA |  |
| BloodGlucoseLevel | 1 | 7 | cmol/L, fmol/L, mol/L, nmol/L, pmol/L, μmol/L |  |
| SpecificVolume | 2 | 8 | L/kg, cm³/g, dL/g, mL/g, mL/kg, mm³/g, mm³/kg | mm³/kg |
| ForcePerArea | 8 | 14 | N/cm², N/mm², N/m², kN/m², kg/(m·s²), pPa |  |
| DisplacementCurrent | 6 | 12 | GA, PA, TA, aA, fA, nA |  |
| TotalCurrent | 6 | 12 | GA, PA, TA, aA, fA, nA |  |
| ElectricCurrent | 6 | 12 | GA, PA, TA, aA, fA, nA |  |
| RotationalFrequency | 5 | 11 | /ms, /s, PHz, c/s, mHz, rev/min |  |
| SpectralRadiantEnergyDensity | 1 | 7 | Pa/m, hPa/m, kPa/m, kPa/mm, mPa/m, pPa/km |  |
| CurrentLinkage | 6 | 12 | GA, PA, TA, aA, fA, nA |  |
| RotationalFrequency | 5 | 11 | /ms, /s, PHz, c/s, mHz, rev/min |  |
| MagneticTension | 6 | 12 | GA, PA, TA, aA, fA, nA |  |
| TemperaturePerTime | 1 | 7 | K/h, K/min, K/s, °C/a, °C/h, °C/min |  |
| CatalyticActivity | 1 | 7 | kmol/h, mkat, mol/h, nkat, pkat, μkat |  |
| MassPerLength | 1 | 7 | g/km, g/m, g/mm, kg/km, kg/mm, mg/m |  |
| PlaneAngle | 3 | 9 | ', gon, grad, mil{NATO}, rev, ° |  |
| LinearDensity | 1 | 7 | g/km, g/m, g/mm, kg/km, kg/mm, mg/m |  |
| SpecificHeatCapacity | 1 | 6 | J/(g·K), J/(g·°C), J/(kg·K), J/(kg·°C), kJ/(kg·K) |  |
| SpecificEnergy | 1 | 6 | J/g, J/kg, MJ/kg, N·m/kg, kJ/kg, mJ/g | J/kg |
| Conductance | 4 | 8 | MS, dS, nS, pS |  |
| SpecificHeatCapacityAtConstantPressure | 1 | 5 | J/(g·K), J/(g·°C), J/(kg·K), J/(kg·°C), kJ/(kg·K) | J/(kg·°C) |
| Force | 5 | 9 | GN, N, cN, dN, nN | N |
| MolarFlowRate | 3 | 7 | kmol/h, kmol/min, mol/h, mol/min |  |
| Area | 6 | 10 | a, cm², daa, dm², ha, km², mm², nm², μm² | cm², dm², mm², nm², μm² |
| Temperature | 2 | 6 | K, MK, daK, mK |  |
| PowerPerArea | 5 | 9 | J/(cm²·d), MJ/(m²·d), kW/m², nW/m² |  |
| SpecificHeatCapacityAtSaturation | 1 | 5 | J/(g·K), J/(g·°C), J/(kg·K), J/(kg·°C), kJ/(kg·K) | J/(kg·°C) |
| StressOpticCoefficient | 1 | 5 | /MPa, m²/N, nm/(cm·MPa), nm/(mm·MPa) |  |
| AreaPerTime | 1 | 5 | cm²/s, mm²/s, m²/h, m²/s |  |
| Admittance | 4 | 8 | MS, dS, nS, pS |  |
| TimeTemperature | 1 | 5 | K·d, °C·d, °C·h, °C·wk |  |
| ActivityConcentration | 1 | 5 | Bq/L, mBq/L, nBq/L, μBq/L |  |
| SpecificEntropy | 1 | 5 | J/(g·K), J/(g·°C), J/(kg·K), J/(kg·°C), kJ/(kg·K) | J/(kg·°C) |
| SpecificHeatCapacityAtConstantVolume | 1 | 5 | J/(g·K), J/(g·°C), J/(kg·K), J/(kg·°C), kJ/(kg·K) | J/(kg·°C) |
| KermaRate | 1 | 5 | mGy/s, nGy/s, μGy/s, μSv/h |  |
| BatteryCapacity | 1 | 5 | A·h, kA·h, mA·h, mA·s |  |
| MolarFluxDensity | 3 | 6 | mmol/(m²·h), nmol/(m²·s), μmol/(m²·h) |  |
| ElectromagneticWavePhaseSpeed | 5 | 8 | cm/s, km/s, m/min, mm/min, mm/s, μm/min, μm/s | cm/s, km/s, mm/s, μm/s |
| AngularMomentum | 2 | 5 | N·m·s, aJ·s, eV·s, kg·m²/s | aJ·s |
| AngularImpulse | 2 | 5 | N·m·s, aJ·s, eV·s, kg·m²/s | aJ·s |
| HydraulicPermeability | 6 | 9 | cm², d, dm², km², md, mm², nm², μm² | cm², dm², mm², nm², μm² |
| LevelWidth | 10 | 13 | nJ, pJ, μJ |  |
| InverseLength | 7 | 10 | /cm, /km, /mm, /nm, /pm, /μm, m/ha, m/m², mm/m² | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| AmountOfSubstance | 5 | 8 | cmol, nmol, pmol |  |
| Acceleration | 2 | 5 | cm/s², kPa·m²/g, km/s², mm/s² | cm/s² |
| Conductivity | 9 | 12 | S/cm, mS/cm, nS/cm, μS/cm | S/cm |
| ElectrolyticConductivity | 9 | 12 | S/cm, mS/cm, nS/cm, μS/cm | S/cm |
| MagneticVectorPotential | 1 | 4 | Wb/m, Wb/mm, kWb/m |  |
| LagrangeFunction | 10 | 13 | nJ, pJ, μJ |  |
| ExtentOfReaction | 5 | 8 | cmol, nmol, pmol |  |
| HamiltonFunction | 10 | 13 | nJ, pJ, μJ |  |
| LinearAcceleration | 2 | 5 | cm/s², kPa·m²/g, km/s², mm/s² | cm/s² |
| IonicStrength | 8 | 11 | cmol/kg, fmol/kg, kmol/kg, mmol/g, mmol/kg, nmol/g, nmol/kg, pmol/kg, μmol/g, μmol/kg | cmol/kg, fmol/kg, kmol/kg, mmol/kg, nmol/kg, pmol/kg, μmol/kg |
| TotalLinearStoppingPower | 1 | 4 | MeV/cm, eV/m, keV/μm |  |
| ExchangeIntegral | 10 | 13 | nJ, pJ, μJ |  |
| LinearEnergyTransfer | 1 | 4 | MeV/cm, eV/m, keV/μm |  |
| AmountOfSubstancePerMass | 8 | 11 | cmol/kg, fmol/kg, kmol/kg, mmol/g, mmol/kg, nmol/g, nmol/kg, pmol/kg, μmol/g, μmol/kg | cmol/kg, fmol/kg, kmol/kg, mmol/kg, nmol/kg, pmol/kg, μmol/kg |
| MassSpecificBiogeochemicalRate | 1 | 4 | mg/(g·h), mg/(kg·d), μg/(g·h) |  |
| SoundPressureLevel | 1 | 3 | dB, dBmW |  |
| ReciprocalMass | 1 | 3 | /kg, /mg |  |
| LinearMomentum | 1 | 3 | N·s, kg·m/s |  |
| MagneticAreaMoment | 1 | 3 | J/T, eV/T |  |
| MomentOfInertia | 1 | 3 | kg·cm², kg·mm² |  |
| SoundReductionIndex | 1 | 3 | dB, dBmW |  |
| MassAbsorptionCoefficient | 1 | 3 | cm²/g, m²/g |  |
| CoefficientOfHeatTransfer | 1 | 3 | kW/(m²·K), kg/(s³·K) |  |
| SoundExposureLevel | 1 | 3 | dB, dBmW |  |
| MolarMass | 1 | 3 | g/mol, kg/kmol |  |
| MassEnergyTransferCoefficient | 1 | 3 | cm²/g, m²/g |  |
| SpecificSurfaceArea | 1 | 3 | cm²/g, m²/g |  |
| Flux | 1 | 3 | /(s·m²), μm/(L·d) |  |
| MassAttenuationCoefficient | 1 | 3 | cm²/g, m²/g |  |
| Capacitance | 6 | 8 | fF, kF |  |
| DynamicViscosity | 2 | 4 | kg/(m·h), kg/(m·s), mPa·s | mPa·s |
| MagneticMoment | 1 | 3 | J/T, eV/T |  |
| SoundPowerLevel | 1 | 3 | dB, dBmW |  |
| MolarVolume | 3 | 5 | L/mol, L/μmol, cm³/mol | cm³/mol |
| MagneticFlux | 2 | 4 | N·m/A, kWb |  |
| PoyntingVector | 5 | 7 | kW/m², nW/m² |  |
| MagneticFluxPerLength | 1 | 3 | T·m, V·s/m |  |
| LuminousIntensity | 1 | 3 | kcd, mcd |  |
| LengthTemperature | 1 | 3 | m·K, °C·cm |  |
| InverseVolume | 3 | 5 | /L, /cm³, /mL, /mm³ | 1/cm³, 1/mm³ |
| RotationalMass | 1 | 3 | kg·cm², kg·mm² |  |
| Compressibility | 1 | 3 | /MPa, /Pa |  |
| Viscosity | 2 | 4 | kg/(m·h), kg/(m·s), mPa·s | mPa·s |
| MolarRefractivity | 3 | 5 | L/mol, L/μmol, cm³/mol | cm³/mol |
| VolumeThermalExpansion | 2 | 4 | L/K, mL/K |  |
| Momentum | 1 | 3 | N·s, kg·m/s |  |
| Emissivity | 1 | 3 | #, 一 |  |
| InverseTemperature | 1 | 2 | /MK |  |
| ParticleFluence | 1 | 2 | /(m·nm) |  |
| ShearModulus | 8 | 9 | pPa |  |
| BulkModulus | 8 | 9 | pPa |  |
| ThermalResistivity | 1 | 2 | m·K/W |  |
| PowerPerElectricCharge | 2 | 3 | mV/min |  |
| SpecificModulus | 2 | 3 | GPa·cm³/g, km²/s² | km²/s² |
| Reactance | 7 | 8 | nΩ |  |
| TorquePerAngle | 1 | 2 | kN·m/° |  |
| IsothermalCompressibility | 1 | 2 | /MPa |  |
| Impedance | 7 | 8 | nΩ |  |
| Polarisability | 1 | 2 | C²·m²/J |  |
| ModulusOfImpedance | 7 | 8 | nΩ |  |
| LengthMass | 1 | 2 | g·mm |  |
| VolumetricFlux | 1 | 2 | mL/(cm²·s) |  |
| ThermalConductivity | 1 | 2 | kW/(m·K) |  |
| Period | 9 | 10 | Ms |  |
| ParticleFluenceRate | 1 | 2 | μm/(L·d) |  |
| TemperatureGradient | 1 | 2 | K/m |  |
| MagneticDipoleMoment | 1 | 2 | Wb·m |  |
| Inductance | 5 | 6 | kH |  |
| MagneticField | 4 | 5 | kT |  |
| SurfaceCoefficientOfHeatTransfer | 1 | 2 | kW/(m²·K) |  |
| MeasurementUnitForAQuantityApproximatelyProportionalToThermalInertia | 1 | 2 | /MK |  |
| LuminousFluxPerArea | 1 | 2 | cd/m² |  |
| RelativePressureCoefficient | 1 | 2 | /MK |  |
| TemperatureAmountOfSubstance | 1 | 2 | mol·K |  |
| NuclearQuadrupoleMoment | 6 | 7 | cm², dm², km², mm², nm², μm² | cm², dm², mm², nm², μm² |
| Permeance | 5 | 6 | kH |  |
| Fugacity | 8 | 9 | pPa |  |
| MagneticFluxDensity | 4 | 5 | kT |  |
| AreaTime | 1 | 2 | cm²·s |  |
| MassicActivity | 3 | 4 | mBq/g, mBq/kg, μBq/kg | mBq/kg, μBq/kg |
| VolumetricHeatCapacity | 2 | 3 | cal/(cm³·K) |  |
| Permittivity | 5 | 6 | F/km, nF/m, pF/m, μF/km, μF/m | F/km, nF/m, pF/m, μF/m |
| ExpansionRatio | 1 | 2 | /MK |  |
| CombinedNonEvaporativeHeatTransferCoefficient | 1 | 2 | kW/(m²·K) |  |
| EnergyDensity | 2 | 3 | MJ/m³, W·h/m³ | MJ/m³ |
| ModulusOfElasticity | 8 | 9 | pPa |  |
| Resistance | 7 | 8 | nΩ |  |
| SpecificAcousticImpedance | 1 | 2 | kg/(m²·s) |  |
| VolumePerUnitArea | 1 | 2 | m³/ha |  |
| TorsionalSpringConstant | 1 | 2 | kN·m/° |  |
| IsentropicCompressibility | 1 | 2 | /MPa |  |
| MassPerEnergy | 1 | 2 | kg/GJ |  |
| InversePressure | 1 | 2 | /MPa |  |
| SpecificActivity | 3 | 4 | mBq/g, mBq/kg, μBq/kg | mBq/kg, μBq/kg |
| InverseMagneticFlux | 1 | 2 | /Wb |  |
| Length | 11 | 12 | AU, fm | fm |
| PhaseCoefficient | 7 | 7 | /cm, /km, /mm, /nm, /pm, /μm | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| AngularReciprocalLatticeVector | 7 | 7 | /cm, /km, /mm, /nm, /pm, /μm | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| AttenuationCoefficient | 7 | 7 | /cm, /km, /mm, /nm, /pm, /μm | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| Permeability | 3 | 3 | nH/m, μH/m | nH/m, μH/m |
| LinearIonization | 7 | 7 | /cm, /km, /mm, /nm, /pm, /μm | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| LinearAttenuationCoefficient | 7 | 7 | /cm, /km, /mm, /nm, /pm, /μm | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| RadiantEnergyDensity | 2 | 2 | MJ/m³ | MJ/m³ |
| TorquePerLength | 2 | 2 | kN·m/m | kN·m/m |
| DiffusionCoefficient | 3 | 3 | cm²/s, mm²/s | cm²/s, mm²/s |
| MomentOfForce | 8 | 8 | MN·m, N·cm, dN·m, mN·m | N·cm, dN·m, m·MN, m·mN |
| Permeability | 3 | 3 | nH/m, μH/m | nH/m, μH/m |
| DisplacementCurrentDensity | 5 | 5 | MA/m² | MA/m² |
| ElectricField | 7 | 7 | V/cm | V/cm |
| SoundVolumeVelocity | 3 | 3 | cm³/s, dm³/s | cm³/s, dm³/s |
| RecombinationCoefficient | 3 | 3 | cm³/s, dm³/s | cm³/s, dm³/s |
| LinearAbsorptionCoefficient | 7 | 7 | /cm, /km, /mm, /nm, /pm, /μm | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| SecondAxialMomentOfArea | 3 | 3 | cm⁴, mm⁴ | cm⁴, mm⁴ |
| SectionModulus | 6 | 6 | cm³, dam³, dm³, mm³, μm³ | cm³, dam³, dm³, mm³, μm³ |
| Action | 2 | 2 | aJ·s | aJ·s |
| Torque | 8 | 8 | MN·m, N·cm, dN·m, mN·m | N·cm, dN·m, m·MN, m·mN |
| Curvature | 7 | 7 | /cm, /km, /mm, /nm, /pm, /μm | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| SecondPolarMomentOfArea | 3 | 3 | cm⁴, mm⁴ | cm⁴, mm⁴ |
| RadiantFluence | 5 | 5 | GJ/m², J/cm², MJ/m² | GJ/m², J/cm², MJ/m² |
| StandardGravitationalParameter | 2 | 2 | km³/s² | km³/s² |
| DiffusionCoefficient | 3 | 3 | cm²/s, mm²/s | cm²/s, mm²/s |
| PressureCoefficient | 4 | 4 | MPa/K | MPa/K |
| Mobility | 2 | 2 | cm²/(V·s) | cm²/(V·s) |
| ElectricCurrentDensity | 5 | 5 | MA/m² | MA/m² |
| SecondMomentOfArea | 3 | 3 | cm⁴, mm⁴ | cm⁴, mm⁴ |
| EnergyPerTemperature | 3 | 3 | kJ/K | kJ/K |
| ElectricFieldStrength | 7 | 7 | V/cm | V/cm |
| Entropy | 3 | 3 | kJ/K | kJ/K |
| TotalCurrentDensity | 5 | 5 | MA/m² | MA/m² |
| VolumicElectromagneticEnergy | 2 | 2 | MJ/m³ | MJ/m³ |
| ElectricChargeDensity | 8 | 8 | C/cm³, C/mm³, GC/m³, MC/m³, kC/m³, mC/m³, μC/m³ | C/cm³, C/mm³, GC/m³, MC/m³, kC/m³, mC/m³, μC/m³ |
| ElectromagneticEnergyDensity | 2 | 2 | MJ/m³ | MJ/m³ |
| ThermalDiffusionCoefficient | 3 | 3 | cm²/s, mm²/s | cm²/s, mm²/s |
| ReactionRateConstant | 2 | 2 | cm³/(mol·s) | cm³/(mol·s) |
| PropagationCoefficient | 7 | 7 | /cm, /km, /mm, /nm, /pm, /μm | 1/cm, 1/km, 1/mm, 1/nm, 1/pm, 1/μm |
| ElectricChargeVolumeDensity | 8 | 8 | C/cm³, C/mm³, GC/m³, MC/m³, kC/m³, mC/m³, μC/m³ | C/cm³, C/mm³, GC/m³, MC/m³, kC/m³, mC/m³, μC/m³ |
| EnergyFluence | 5 | 5 | GJ/m², J/cm², MJ/m² | GJ/m², J/cm², MJ/m² |


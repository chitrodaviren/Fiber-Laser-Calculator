# Fiber Laser Calculator

Private GitHub project for fiber-laser cutting time and costing.

### Core calculation
- Running length (m) = running mm / 1000
- Cutting time (seconds) = running length (m) / cutting speed (m/s)

### Parameter logic
Material and thickness come from the user's FSM collection. Nozzle, gas and other CypCut settings are ignored. Only cutting speed in m/s is used.

Parameter data can be imported as JSON. When the FSM files are supplied, their material/thickness naming can be mapped into the database.

### Costing
- Per meter
- Per time
- Full cost with material, laser, consumables, labour, profit and GST

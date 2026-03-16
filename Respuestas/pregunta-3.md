db.sensores.find(
  { zona: "planta" },
  { sensor_id: 1, temperatura: 1, _id: 0 }
)
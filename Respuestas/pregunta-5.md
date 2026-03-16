db.sensores.aggregate([
  {
    $group: {
      _id: "$zona",
      temperatura_promedio: { $avg: "$temperatura" }
    }
  }
])
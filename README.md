# make-a-car

@Override
    public boolean unparkVehicleBtn(String licensePlate, VehicleType type) {
        
        Vehicle vehicle = new Vehicle(licensePlate, type.getSpotsNeeded(), type);
        
        return parkingLot.unparkVehicle(vehicle);
    }

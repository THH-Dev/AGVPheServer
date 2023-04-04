// load docker image
$ docker load -i ./thhfleet.0.0.9.tar

// run docker container
$ docker-compose up -d

// migration database
$ docker exec -it fleetmanager /app/RobotNet5.FleetManager.Server --seed

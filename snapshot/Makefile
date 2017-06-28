.PHONY: all controller provisioner clean

all: controller provisioner

controller:
	go build -o _output/bin/snapshot-controller cmd/snapshot-controller/snapshot-controller.go

provisioner:
	go build -o _output/bin/snapshot-provisioner cmd/snapshot-pv-provisioner/snapshot-pv-provisioner.go

clean:
	-rm -rf _output

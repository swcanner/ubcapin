What we have:

initial dataset
raw pdbs (`rcsb_pdb`)
pdbs only with protein + glycan (`refined_xtal_pdb`)

What we need:

DiffDock-Holo:
	RCSB protein only files

DiffDock-AF3:
	AF3 predictions of FASTA only

AF3:
	JSON files for input in single directory

Chai:
	All ready for online server input

RFAA:
	All ready for online server input

Boltz:
	YAML file for prediction
	see:	https://github.com/jwohlwend/boltz/blob/main/docs/prediction.md

Future work:

Run and deposit:
	DiffDock-Holo
	DiffDock-AF3
	AF3
	Chai
	RFAA
	Boltz

Analyze:
	DiffDock-Holo
        DiffDock-AF3
        AF3
        Chai
        RFAA
        Boltz

Analysis metrics:
	Protein-RMS
	L-RMS
	Dice
	Fnat

	DockQC - needs to be developed


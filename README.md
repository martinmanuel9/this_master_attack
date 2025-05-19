<<<<<<< HEAD
# How to run the code tcis master attack

- step 1: kafka data collection and pre-processing
  set H_BAU_MODE == 0;
  select the layer needed to be collected data from ['application', 'network', 'system'] in the configuration of "h_bau_online.py";
  run "python h_bau_online.py" to start collect data.
- step 2: train offline (initial) model
  set the training parameters in the configuration of "train.py";
  run "python train.py" to train models.
- step 3: train offline (initial) model
  set H_BAU_MODE == 1;
  run "python h_bau_online.py" to start online learning and real-time analysis.
=======
# this_master_attack
tcis_master_attack
>>>>>>> 095d618e51e345f09012c2eccabbfd013ae5b01c

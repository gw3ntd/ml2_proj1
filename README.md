# Manual Training 
## Good Hyperparams
### Trial 1
- {'hyperparams': {'learning_rate': 0.005, 'batch_size': 64, 'epochs': 50, 'num_layers': 3, 'neurons': 128}, 'final_val_acc': 0.42820000648498535, 'final_train_acc': 0.44664445519447327, 'run_id': 3}

- {'hyperparams': {'learning_rate': 0.01, 'batch_size': 128, 'epochs': 200, 'num_layers': 2, 'neurons': 64}, 'final_val_acc': 0.3555999994277954, 'final_train_acc': 0.3678888976573944, 'run_id': 4}

- **Best:** {'hyperparams': {'learning_rate': 0.005, 'batch_size': 128, 'epochs': 100, 'num_layers': 2, 'neurons': 128}, 'final_val_acc': 0.45159998536109924, 'final_train_acc': 0.4699999988079071, 'run_id': 6}

- {'hyperparams': {'learning_rate': 0.005, 'batch_size': 64, 'epochs': 100, 'num_layers': 2, 'neurons': 64}, 'final_val_acc': 0.43779999017715454, 'final_train_acc': 0.46142223477363586, 'run_id': 8}

- **Second Best:** {'hyperparams': {'learning_rate': 0.005, 'batch_size': 64, 'epochs': 100, 'num_layers': 2, 'neurons': 128}, 'final_val_acc': 0.41940000653266907, 'final_train_acc': 0.438400000333786, 'run_id': 9}

### Trial 2
- {'hyperparams': {'learning_rate': 0.005, 'batch_size': 32, 'epochs': 100, 'num_layers': 2, 'neurons': 256}, 'final_val_acc': 0.3831999897956848, 'final_train_acc': 0.39802223443984985, 'run_id': 1}

- {'hyperparams': {'learning_rate': 0.005, 'batch_size': 64, 'epochs': 100, 'num_layers': 2, 'neurons': 128}, 'final_val_acc': 0.40939998626708984, 'final_train_acc': 0.42844444513320923, 'run_id': 3}

- {'hyperparams': {'learning_rate': 0.005, 'batch_size': 64, 'epochs': 70, 'num_layers': 1, 'neurons': 256}, 'final_val_acc': 0.41280001401901245, 'final_train_acc': 0.426622211933136, 'run_id': 4}

- {'hyperparams': {'learning_rate': 0.005, 'batch_size': 64, 'epochs': 70, 'num_layers': 1, 'neurons': 256}, 'final_val_acc': 0.39800000190734863, 'final_train_acc': 0.4125555455684662, 'run_id': 5}

### My review
> Although none of these accuracies were very good (at all), the two best had many hyperparameters in common. They had the same learning rate, the same number of epochs, the same number of layers, and the same number of neurons. The only difference was the batch size. 

# Short-Squeeze-1def get_primes(self, filename):
  Reads in from a txt file and appends all numbers in said text file to the primes_list variable.

def get_load_factor(self):
  Returns the load factor of the hash table.

def my_hash(self, key, num):
  Returns the hash value to be used in the hash table.

def find_capacity(self):
  Sets the capacity variable to the correct value.

def rehash(self):
  Utilizes quadratic probing to rehash the entire hash_table variable. Increases the capacity to the next known suitable prime number.

def insert(self, ticker, ame=None, prev_close=None, open_p=None, close=None):
  Inserts a ticker fed from the runner program into the hash_table variable. Uses my_hash and rehash.

def remove(self, ticker):
  Removes said ticker from the hash_table variable.

def get(self, ticker):
  Returns the pointer to the node container the ticker.

def print_tcker(self):
  Prints every ticker in the hash_table variable.

def get_avg_volume(self, ticker, days=0):
  Returns the average volume for the ticker that is sent in.

def init_run(self, ticker):
  Called by the runner program, will test to see if the day's volume is above 20% above the average volume. If it is, it will add 1 to the days_above_twenty variable as found in the ss_ds_node.py file.

# chef

Some Useful commands:
  $ knife environment show DEV -F json
  $ knife environment show DEV -F json > DEV.json
  $ knife environment from file DEV.json
  $ knife data bag show DEV DEV_creds --secret-file ~/.ssh/encrypted_data_bag_secret -F json

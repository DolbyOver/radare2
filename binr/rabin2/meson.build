
executable('rabin2', 'rabin2.c',
  include_directories: include_directories([
    '../../libr/include',
	platform_binrinc
  ]),
  link_with: [r_util, r_cons, r_config, r_hash, r_io, r_crypto, r_core],
  objects: [
    r_sdb.extract_all_objects(),
	r_bin.extract_all_objects()
  ],    
  install: true
)

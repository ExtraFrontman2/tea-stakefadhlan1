import { stakeCrypto } from './stake';

const amount = 10; // Jumlah cryptocurrency yang akan di-stake
stakeCrypto(amount)
  .then(response => {
    console.log('Staking berhasil:', response);
  })
  .catch(error => {
    console.error('Staking gagal:', error);
  });

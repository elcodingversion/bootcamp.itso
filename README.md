# bootcamp.itso | tugas.1
let karyawan = {
    nama: 'Fiersha',
    usia: 32,
    member: true,
    gajiBulanan: 870000
};

let gajiTahunan = karyawan.gajiBulanan * 12;
let mendapatBonus = karyawan.usia > 30 && karyawan.member;

console.log(`Nama: ${karyawan.nama}`);
console.log(`Usia: ${karyawan.usia}`);
console.log(`Gaji Bulanan: ${karyawan.gajiBulanan}`);
console.log(`Gaji Tahunan: ${gajiTahunan}`);
console.log(`Status Karyawan: ${karyawan.member}`);
console.log(`Bonus: ${mendapatBonus}`);

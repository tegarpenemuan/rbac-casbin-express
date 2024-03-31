## Penjelasan singkat

semua aturan yang bisa diakses akan di catat di `basic_policy.csv`<br/><br/>
untuk menjalankan ketikan `npm run dev` dan akses di `http://localhost:3000/protected`<br/><br/>
Patikan aturan ini: <br/>
`const authorized = await enforcer.enforce("alice", "data1", "read");`<br/>
ada di file `basic_policy.csv`. Jika ada maka akan menampilkan hasil `You're in!` dan jika tidak ada akan menampilkan `Not Authorized`

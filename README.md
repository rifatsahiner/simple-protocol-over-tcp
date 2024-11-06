# simple-protocol-over-tcp
Simplest possible server-client protocol for command based communication between two peers over TCP

// simple-protocol-over-tcp diye repo aç bizim stx-length-command-payload-crc-etx paket formatı ve uos-task yapısı ile protokolü implemente et
// SpotSocket->SpotClient ve
// SpotSocket->SpotServer class'ları olacak
// UDP olacak (server-client yok), ack/nack/retry kendimiz yapacağız (nack-> unknown command, improper payload etc.)
// sequence olacak cevap gelemden yeni komut yollayabileceğiz
bu şekilde not almıştım ama tcp olması lazım
asıl insanların istediği şu;
komut tipleri bir yerde tanımlanacak
length olacak, length sayesinde alınan tcp paketinden payload çekilebilecek
response için bir mekanizma olabilir


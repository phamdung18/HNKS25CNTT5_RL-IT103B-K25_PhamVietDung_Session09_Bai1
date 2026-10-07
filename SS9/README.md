Dòng lệnh sai là const basePrice = bookingReservation.priceKey;
`priceKey` là biến có giá trị là `roomPrice`. Dùng dấu chấm làm JavaScript tìm thuộc tính tên là `priceKey`, nên kết quả là `undefined` khi tính phụ thu và tổng tiền với `undefined`, kết quả bị `NaN`


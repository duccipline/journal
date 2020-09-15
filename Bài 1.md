# Bài 1

Cho dãy `n+1` số nguyên dương gồm các giá trị trong phạm vi `[1, n]`. Dữ liệu đảm bảo có ít nhất 1 giá trị xuất hiện nhiều hơn 1 lần. In ra giá trị đó, và dãy số dữ liệu đề bài.

| Input | Output |
|-------|--------|
| 10 <br> 5 9 7 8 10 2 4 6 9 1 3 | 9 <br> 5 9 7 8 10 2 4 6 9 1 3 |

* n ≤ 10<sup>3</sup>
* n ≤ 10<sup>6</sup>
* n ≤ 10<sup>6</sup> và bộ nhớ (n + 5) x 4 bytes
* n ≤ 10<sup>6</sup> và bộ nhớ (n + 5) x 4 bytes và không được sắp xếp lại dãy
* n ≤ 10<sup>6</sup> và bộ nhớ (n + 5) x 4 bytes và độ phức tạp `O(N)`

# Bài 1*

Cho `2n+1` số nguyên (giá trị các số ≠ 0, giá trị tuyệt đối ≤ _n_), có đúng một giá trị xuất hiện 2 lần, bộ nhớ (2n + 5) x 4 bytes và không được sắp xếp lại dãy

| Input | Output | 
|-------|--------|
| 5 <br> 1 2 3 4 5 -1 -2 -3 -4 -5 3 | 3
  
# Bài 2

## Bài 2.1

<details close>
Cho 1 file gồm `n` số nguyên có giá trị trong phạm vi `[1, n]`. Dữ liệu đảm bảo có duy nhất 1 giá trị xuất hiện 1 lần, tất cả các giá trị còn lại xuất hiện 2 lần. Tìm giá trị xuất hiện lẻ lần.
</details>

## Bài 2.2

Cho 1 file gồm `n-1` số nguyên phân biệt có giá trị trong phạm vi `[1, n]`. Tìm giá trị bị thiếu

* n ≤ 10<sup>9</sup>

## Bài 2.3

Cho 1 file gồm `n` số nguyên phân biệt có giá trị trong phạm vi `[1, n]`. Trong các giá trị thuộc phạm vi `[1, n]` có 1 giá trị xuất hiện 2 lần, và 1 giá trị không xuất hiện trong file. Tìm giá trị không xuất hiện.

* n ≤ 10<sup>9</sup>

# Bài 3 

## Bài 3.1

<details close>
Cho 1 file gồm `n` số nguyên có giá trị trong phạm vi `[1, n]`. Dữ liệu đảm bảo có duy nhất 2 giá trị (phân biệt) xuất hiện 1 lần, tất cả các giá trị còn lại xuất hiện 2 lần. Tìm 2 giá trị xuất hiện lẻ lần.
</details>

## Bài 3.2

Cho 1 file gồm `n-2` số nguyên phân biệt có giá trị trong phạm vi `[1, n]`. Tìm 2 giá trị bị thiếu

* n ≤ 10<sup>9</sup>

# Bài 4

Cho dãy `n` số nguyên, mỗi số nguyên có giá trị tuyệt đối ≤ 10<sup>9</sup>. Tìm 2 giá trị trong dãy sao cho **giá trị tuyệt đối của hiệu 2 giá trị** đó là **lớn nhất**.

| Input | Output |
|-------|--------|
| 10 <br> 1 4 -3 5 2 9 7 -5 6 8 | 14 |

# Bài 4*

Cho dãy `n` số nguyên a<sub>i</sub>, |a<sub>i</sub>| ≤ 10<sup>9</sup>. Tìm 2 giá trị `i`, `j` sao cho giá trị  

* | _a<sub>i</sub>_  - _a<sub>j</sub>_ | + | _i_ - _j_ | là lớn nhất

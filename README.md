| NAME: | Silfa Salsa Bila Putri |
| --- | --- |
| NIM: | 312310607 |
| KELAS: | TI.23.A6 |
- # Home
```
<div class="jumbotron text-center">
    <h1 class="display-4">Welcome To Silfa Online Food!</h1>
    <p class="lead">Temukan Makanan Terbaik Dengan Harga Terjangkau</p>
    <a class="btn btn-primary btn-lg" href="#" role="button">Belanja Sekarang</a>
</div>

<!-- Featured Products Section -->
<div class="container mt-5">
    <h2 class="text-center">Makanan yang direkomendasikan</h2>
    <div class="row">
        <?php
        // Dummy products array
        $products = [
            ["name" => "Ayam Goreng", "price" => "Rp15.000", "image" => "https://img-global.cpcdn.com/recipes/ff70ae9c035a4aba/400x400cq70/photo.jpg"],
            ["name" => "Ayam Goreng Bawang Putih", "price" => "Rp20.000", "image" => "https://images.tokopedia.net/img/cache/500-square/VqbcmM/2023/6/21/857e1eb1-9557-4c16-bf89-059c8b943708.jpg"],
            ["name" => "Ayam Geprek", "price" => "Rp15.000", "image" => "https://www.masakapahariini.com/wp-content/uploads/2023/03/shutterstock_1949306203-500x300.jpg"],
            ["name" => "Ayam Bakar", "price" => "Rp15.000", "image" => "https://images.tokopedia.net/img/JFrBQq/2023/11/16/2c781909-607e-413f-aab2-8b8715487416.jpg"]
        ];

        // Display products in a grid
        foreach ($products as $product) {
            echo '
            <div class="col-md-3">
                <div class="card mb-4 shadow-sm">
                    <img src="' . $product['image'] . '" class="card-img-top" alt="' . $product['name'] . '">
                    <div class="card-body">
                        <h5 class="card-title">' . $product['name'] . '</h5>
                        <p class="card-text">' . $product['price'] . '</p>
                        <a href="#" class="btn btn-primary">Tambahkan ke Keranjang</a>
                    </div>
                </div>
            </div>';
        }
        ?>
    </div>
</div>

<!-- Bootstrap and jQuery JavaScript -->
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.6.0/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
```
![Screenshot 2024-11-04 213813](https://github.com/user-attachments/assets/d8dbc3d3-320d-4e07-8081-eb87da9596c3)

- # About
```
<div class="container mt-5">
    <h2 class="text-center">About Silfa Online Food</h2>
    <p class="lead text-center">Pelajari lebih lanjut tentang misi, nilai, dan tim kami.</p>
    <div class="row mt-4">
        <div class="col-md-6">
            <h3>Kisah kami</h3>
            <p>OnlineStore didirikan dengan misi menyediakan makanan yang berkualitas tinggi kepada pelanggan. Tim kami
                berdedikasi untuk menawarkan pengalaman berbelanja makanan terbaik dengan berfokus pada kepuasan
                pelanggan dan pengiriman cepat.</p>
        </div>
        <div class="col-md-6">
            <h3>Visi misi kita</h3>
            <ul>
                <li>Kepuasan Pelanggan</li>
                <li>Produk Berkualitas</li>
                <li>Integritas dan Transparansi</li>
                <li>Inovasi</li>
            </ul>
        </div>
    </div>
</div>


<!-- Bootstrap and jQuery JavaScript -->
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.6.0/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
```
![Screenshot 2024-11-04 213837](https://github.com/user-attachments/assets/339b7f6f-22e9-4fd5-9762-d2f05b0427b8)

- # Contact
```
<div class="container mt-5">
    <h2 class="text-center">Contact Us</h2>
    <p class="lead text-center">We'd love to hear from you. Send us a message using the form below.</p>
    <div class="row justify-content-center mt-4">
        <div class="col-md-8">
            <form action="send_contact.php" method="post">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" class="form-control" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email address</label>
                    <input type="email" class="form-control" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea class="form-control" id="message" name="message" rows="5" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
            </form>
        </div>
    </div>
</div>


<!-- Bootstrap and jQuery JavaScript -->
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.6.0/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
```
![Screenshot 2024-11-04 213853](https://github.com/user-attachments/assets/7e704985-ce2c-42d2-9577-00523675109e)


<template>
    <div class="card h-100">
        <div class="card-body">
            <h5 class="card-title mb-5">Marketplace</h5>
            <div class="card-text">
                <table class="table">
                    <thead>
                        <tr>
                            <th scope="col">Id</th>
                            <th scope="col">Value</th>
                            <th scope="col">Due Date</th>
                            <th scope="col">Price</th>
                            <th scope="col">&nbsp;</th>
                            <th scope="col">&nbsp;</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <th scope="row">1299</th>
                            <td>500</td>
                            <td>2023-1-31</td>
                            <td>250</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">1312</th>
                            <td>2624</td>
                            <td>2023-2-12</td>
                            <td>1000</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">2174</th>
                            <td>1500</td>
                            <td>2023-6-16</td>
                            <td>1400</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">3001</th>
                            <td>10000</td>
                            <td>&nbsp;</td>
                            <td>7000</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">3002</th>
                            <td>12</td>
                            <td>2023-8-19</td>
                            <td>8</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">1299</th>
                            <td>500</td>
                            <td>&nbsp;</td>
                            <td>400</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">1312</th>
                            <td>2624</td>
                            <td>2023-2-12</td>
                            <td>2000</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">2174</th>
                            <td>1500</td>
                            <td>2023-6-16</td>
                            <td>750</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">3001</th>
                            <td>10000</td>
                            <td>&nbsp;</td>
                            <td>8000</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">3002</th>
                            <td>12</td>
                            <td>2023-8-19</td>
                            <td>10</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    setup () {
        const comingSoon = () => {
            alert('Coming soon!');
        }

        return {
            comingSoon,
        }
    }
}
</script>

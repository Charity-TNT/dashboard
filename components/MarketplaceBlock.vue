<template>
    <div class="card h-100">
        <div class="card-body">
            <h5 class="card-title mb-5">Marketplace</h5>
            <div class="card-text">
                <table class="table">
                    <thead>
                        <tr>
                            <th scope="col">Id</th>
                            <th scope="col">Type</th>
                            <th scope="col">Redemption Value</th>
                            <th scope="col">Maturity Date</th>
                            <th scope="col">Sale Price</th>
                            <th scope="col">&nbsp;</th>
                            <th scope="col">&nbsp;</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <th scope="row">1299</th>
                            <td>Red Carpet</td>
                            <td>500 USDC</td>
                            <td>2023-1-31</td>
                            <td>250 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">1312</th>
                            <td>Red Carpet</td>
                            <td>2624 USDC</td>
                            <td>2023-2-12</td>
                            <td>1000 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">2174</th>
                            <td>Red Carpet</td>
                            <td>1500 USDC</td>
                            <td>2023-6-16</td>
                            <td>1400 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">3001</th>
                            <td>White Carpet</td>
                            <td>10000 TNT</td>
                            <td>&nbsp;</td>
                            <td>7000 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">3002</th>
                            <td>Red Carpet</td>
                            <td>12 USDC</td>
                            <td>2023-8-19</td>
                            <td>8 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">1299</th>
                            <td>White Carpet</td>
                            <td>500 TNT</td>
                            <td>&nbsp;</td>
                            <td>400 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">1312</th>
                            <td>Red Carpet</td>
                            <td>2624 USDC</td>
                            <td>2023-2-12</td>
                            <td>2000 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">2174</th>
                            <td>Red Carpet</td>
                            <td>1500 USDC</td>
                            <td>2023-6-16</td>
                            <td>750 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">3001</th>
                            <td>White Carpet</td>
                            <td>10000 TNT</td>
                            <td>&nbsp;</td>
                            <td>8000 USDC</td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-success">Buy Now</button></td>
                            <td><button @click="comingSoon" class="btn btn-sm btn-block btn-info">Make Offer</button></td>
                        </tr>
                        <tr>
                            <th scope="row">3002</th>
                            <td>Red Carpet</td>
                            <td>12 USDC</td>
                            <td>2023-8-19</td>
                            <td>10 USDC</td>
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

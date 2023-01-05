<template>
    <div class="card h-100">
        <div class="card-body">
            <h5 class="card-title mb-5">Leaderboards</h5>
            <div class="card-text">
                <div class="mb-3">
                    <ul class="nav justify-content-center">
                        <li class="nav-item">
                            <button class="btn btn-link nav-link">All Time</button>
                        </li>
                        <li class="nav-item">
                            <button class="btn btn-link nav-link">Monthly</button>
                        </li>
                        <li class="nav-item">
                            <button class="btn btn-link nav-link">Weekly</button>
                        </li>
                        <li class="nav-item">
                            <button class="btn btn-link nav-link">Daily</button>
                        </li>
                    </ul>
                    <table class="table">
                        <thead>
                            <tr>
                                <th scope="col">User</th>
                                <th scope="col">USDC Raised for Charity</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <th scope="row">0x9d...739122</th>
                                <td>750.1110</td>
                            </tr>
                            <tr>
                                <th scope="row">0x4e...BD91e5</th>
                                <td>740.1312</td>
                            </tr>
                            <tr>
                                <th scope="row">0x85...2EF665</th>
                                <td>699.9918</td>
                            </tr>
                            <tr>
                                <th scope="row">0x58...124687</th>
                                <td>501.1239</td>
                            </tr>
                            <tr>
                                <th scope="row">0x8B...58b8D8</th>
                                <td>217.0000</td>
                            </tr>
                            <tr>
                                <th scope="row">0x9d...739122</th>
                                <td>750.1110</td>
                            </tr>
                            <tr>
                                <th scope="row">0x4e...BD91e5</th>
                                <td>740.1312</td>
                            </tr>
                            <tr>
                                <th scope="row">0x85...2EF665</th>
                                <td>699.9918</td>
                            </tr>
                            <tr>
                                <th scope="row">0x58...124687</th>
                                <td>501.1239</td>
                            </tr>
                            <tr>
                                <th scope="row">0x8B...58b8D8</th>
                                <td>217.0000</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
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

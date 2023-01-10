<template>
    <div>
        <h1>Dashboard</h1>
        <div class="row gx-5">
            <div class="col-md-6 mb-4">
                <BalanceBlock/>
            </div>
            <div class="col-md-6 mb-4">
                <SwapBlock/>
            </div>
            <div class="col-md-6 mb-4">
                <WhiteCarpetBlock/>
            </div>
            <div class="col-md-6 mb-4">
                <RedCarpetBlock/>
            </div>
        </div>
        <MarketplaceBlock class="mb-4"/>
        <LeaderboardBlock class="mb-4"/>
    </div>
</template>

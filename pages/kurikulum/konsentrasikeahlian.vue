<template>
    <div class="jurusan mt-5 pt-5">
        <h3 class="m-5">KOMPETENSI KEAHLIAN</h3>
        <div class="scroll-container">
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/tjkt.png" class="card-img-top" alt="Teknik Jaringan Komputer">
                <div class="card-body">
                    <h5 class="card-title">TEKNIK JARINGAN KOMPUTER DAN TELEKOMUNIKASI</h5>
                </div>
            </div>
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/pplg.png" class="card-img-top" alt="Pengembangan Perangkat Lunak">
                <div class="card-body">
                    <h5 class="card-title">PENGEMBANGAN PERANGKAT LUNAK DAN GIM</h5>
                </div>
            </div>
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/tbsm.png" class="card-img-top" alt="Teknik Sepedah Motor">
                <div class="card-body">
                    <h5 class="card-title">TEKNIK SEPEDAH MOTOR</h5>
                </div>
            </div>
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/dkv.png" class="card-img-top" alt="Desain Komunikasi Visual">
                <div class="card-body">
                    <h5 class="card-title">DESAIN KOMUNIKASI VISUAL</h5>
                </div>
            </div>
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/toi.png" class="card-img-top" alt="Teknik Otomasi Industri">
                <div class="card-body">
                    <h5 class="card-title">TEKNIK OTOMASI INDUSTRI</h5>
                </div>
            </div>
        </div>
    </div>
    <div class="jurusan mt-5 pt-5">
        <h3 class="m-5">GURU-GURU</h3>
        <h3 class="m-5">TOTAL : 56</h3>
        <div class="scroll-container">
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/pa adi.png" class="card-img-top" alt="PA ADI">
                <div class="card-body">
                    <h5 class="card-title">PA ADI</h5>
                </div>
            </div>
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/pa hilmi.png" class="card-img-top" alt="PA HILMI">
                <div class="card-body">
                    <h5 class="card-title">PA HILMI</h5>
                </div>
            </div>
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/bu ana.png" class="card-img-top" alt="BU ANA">
                <div class="card-body">
                    <h5 class="card-title">BU ANA</h5>
                </div>
            </div>
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/pa deri.png" class="card-img-top" alt="PA DERI">
                <div class="card-body">
                    <h5 class="card-title">PA DERI</h5>
                </div>
            </div>
            <div class="card mx-5" style="width: 20rem;">
                <img src="/assets/img/kepala sekolah.png" class="card-img-top" alt="KEPALA SEKOLAH">
                <div class="card-body">
                    <h5 class="card-title">KEPALA SEKOLAH</h5>
                </div>
            </div>
        </div>
    </div>
    <div class="stat text-center bg-dark text-light">
        <div>
            <h1>siswa</h1>
            <h2>15000</h2>
        </div>
    </div>
</template>

<style>
.scroll-container {
    display: flex;
    overflow-x: auto;
    gap: 1rem;
    padding: 1rem 0;
    scrollbar-width: thin;
}

.scroll-container::-webkit-scrollbar {
    height: 8px;
}

.scroll-container::-webkit-scrollbar-thumb {
    background-color: #087a8e;
    border-radius: 4px;
}

.scroll-container::-webkit-scrollbar-track {
    background-color: #3297ad;
}

.card {
    flex: 0 0 auto;
}

.stat {
    padding: 2rem;
}

@media (max-width: 768px) {
    .card {
        width: 15rem; /* adjust card width for smaller screens */
    }
}

@media (max-width: 480px) {
    .scroll-container {
        flex-direction: column; /* stack cards vertically on small screens */
    }
}
</style>


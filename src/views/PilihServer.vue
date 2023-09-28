<template>
    <div class="d-flex flex-column justify-content-between align-items-center px-50 py-40">
		<div class="">
			<h2 class="text-black-gray">Pilih Server</h2>
		</div>
        <form class="w-100 d-flex flex-column mt-30">
            <label class="serverlabel">
                <input type="radio" name="radioserver" class="server-radiobtn" checked>
                <span class="servername w-100">Kejaksaan Agung <i class="fas fa-check"></i></span>
            </label>
            <label class="serverlabel">
                <input type="radio" name="radioserver" class="server-radiobtn">
                <span class="servername w-100">Kejati Jawa Timur <i class="fas fa-check"></i></span>
            </label>
            <label class="serverlabel">
                <input type="radio" name="radioserver" class="server-radiobtn">
                <span class="servername w-100">Kejati Sulawesi Selatan <i class="fas fa-check"></i></span>
            </label>
            <label class="serverlabel">
                <input type="radio" name="radioserver" class="server-radiobtn">
                <span class="servername w-100">Kejati Kalimantan Selatan <i class="fas fa-check"></i></span>
            </label>
            <label class="serverlabel">
                <input type="radio" name="radioserver" class="server-radiobtn">
                <span class="servername w-100">Kejati Sumatera Utara <i class="fas fa-check"></i></span>
            </label>
        </form>
		<div class="d-flex justify-content-between align-items-center mt-92 w-100">
			<a @click="$router.go(-1)" class="link-text">
				<i class="fas fa-chevron-left"></i>
				Kembali
			</a>
			<button type="submit" class="btn btn-primary-kejaksaan">SIMPAN</button>
		</div>
	</div>
</template>
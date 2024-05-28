<template>
<div class="container">
	<div class="son">
		<div>野生蓝葡萄</div>
	</div>
	<div class="son2">
		<div>野生蓝葡萄</div>
	</div>
	<div class="son3">
		<div>野生蓝葡萄</div>
	</div>
	<div class="son4">
		<div>野生蓝葡萄</div>
	</div>
	<div class="son5">
		<div>野生蓝葡萄</div>
	</div>
</div>
</template>

<script setup>

</script>

<style scoped>
.container{
	height: 300px;
	width: 100%;
	background-color: aliceblue;
	display: flex;
	flex-direction: row;
	justify-content: space-between;
	align-items: center;
}
.son{
	background-color: aquamarine;
	height: 50%;
	width: 10%;
	display: flex;
	flex-direction: row;
	justify-content: center;
	align-items: center;
}
.son2{
	background-color: darkred;
	height: 50%;
	width: 10%;
	display: flex;
	flex-direction: row;
	justify-content: flex-start;
	align-items: center;
}
.son3{
	background-color: darkblue;
	height: 50%;
	width: 10%;
	display: flex;
	flex-direction: row;
	justify-content: flex-end;
	align-items: center;
}
.son4{
	background-color: darkgreen;
	height: 50%;
	width: 10%;
	display: flex;
	flex-direction: row;
	justify-content: flex-start;
	align-items: flex-start;
}
.son5{
	background-color: darkgoldenrod;
	height: 50%;
	width: 10%;
	display: flex;
	flex-direction: row;
	justify-content: flex-end;
	align-items: flex-end;
}
</style>

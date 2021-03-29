<script>
	import { 
		Logo1, 
		Logo2,
		Logo3,
		Logo4,
		Logo5,
		Logo6,
		Logo7,
		Logo8,
		Logo9,
		Logo10,
		Logo11,
		Logo12,
		Logo13,
		Logo14,
		Logo15,
		Logo16,
		Logo17,
		Logo18,
		Logo19,
		Logo20,
		Logo21,
		Logo22,
		Logo23,
		Logo24,
		Logo25,
		Logo26
	} from 'svelte-logoipsum';
</script>

<main>
	<div class="logo">
		<span>Logo1</span>
		<div>
			<Logo1 />
		</div>
	</div>
	<div class="logo">
		<span>Logo2</span>
		<Logo2 />
	</div>
	<div class="logo">
		<span>Logo3</span>
		<Logo3 />
	</div>
	<div class="logo">
		<span>Logo4</span>
		<Logo4 />
	</div>
	<div class="logo">
		<span>Logo5</span>
		<Logo5 />
	</div>
	<div class="logo">
		<span>Logo6</span>
		<Logo6 />
	</div>
	<div class="logo">
		<span>Logo7</span>
		<Logo7 />
	</div>
	<div class="logo">
		<span>Logo8</span>
		<Logo8 />
	</div>
	<div class="logo">
		<span>Logo9</span>
		<Logo9 />
	</div>
	<div class="logo">
		<span>Logo10</span>
		<Logo10 color1="grey" color2="white" />
	</div>
	<div class="logo">
		<span>Logo11</span>
		<Logo11 />
	</div>
	<div class="logo">
		<span>Logo12</span>
		<Logo12 color1="red" color2="blue" color3="green" />
	</div>
	<div class="logo">
		<span>Logo13</span>
		<Logo13 />
	</div>
	<div class="logo">
		<span>Logo14</span>
		<Logo14 />
	</div>
	<div class="logo">
		<span>Logo15</span>
		<Logo15 />
	</div>
	<div class="logo">
		<span>Logo16</span>
		<Logo16 color1="#e9c46a" color2="#f4a261" color3="#2a9d8f" color4="#e76f51" />
	</div>
	<div class="logo">
		<span>Logo17</span>
		<Logo17 />
	</div>
	<div class="logo">
		<span>Logo18</span>
		<Logo18 />
	</div>
	<div class="logo">
		<span>Logo19</span>
		<Logo19 />
	</div>
	<div class="logo">
		<span>Logo20</span>
		<Logo20 />	
	</div>
	<div class="logo">
		<span>Logo21</span>
		<Logo21 />
	</div>
	<div class="logo">
		<span>Logo22</span>
		<Logo22 />
	</div>
	<div class="logo">
		<span>Logo23</span>
		<Logo23 />
	</div>
	<div class="logo">
		<span>Logo24</span>
		<Logo24 />
	</div>
	<div class="logo">
		<span>Logo25</span>
		<Logo25 />
	</div>
	<div class="logo">
		<span>Logo26</span>
		<Logo26 />
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	.logo {
		margin: 1.5rem 0;
	}

	.logo span {
		display: block;
		margin-bottom: 1rem;
	}

	@media (min-width: 640px) {
		main {
			max-width: 500px;
		}
	}
</style>
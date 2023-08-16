<script lang="ts">
  import { Navbar, NavBrand, NavHamburger, NavLi, NavUl } from "flowbite-svelte";
	import Logo from "../constants/Logo.svelte";
</script>

<Navbar let:hidden let:toggle>
  <NavBrand href="/">
    <Logo />
  </NavBrand>
  <NavHamburger on:click={toggle} />
  <NavUl {hidden}>
    <NavLi href="/" active={true}>Home</NavLi>
    <NavLi href="#">About</NavLi>
    <NavLi href="#">Services</NavLi>
    <NavLi href="#">Pricing</NavLi>
    <NavLi href="#">Contact</NavLi>
  </NavUl>
</Navbar>

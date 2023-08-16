<script>
	import { Footer, FooterCopyright, FooterIcon, FooterLink, FooterLinkGroup } from "flowbite-svelte";
  import Icon from "@iconify/svelte";
	import Logo from "../constants/Logo.svelte";

</script>
<Footer footerType="logo">
  <div class="flex items-center justify-between pb-5">
    <a href="/#">
      <Logo />
    </a>
    <FooterLinkGroup ulClass="flex  flex-wrap items-center mb-6 text-sm text-gray-500 sm:mb-0">
      <FooterLink href="/#">About</FooterLink>
      <FooterLink href="/#">Services</FooterLink>
      <FooterLink href="/#">Pricing</FooterLink>
      <FooterLink href="/#">Contact</FooterLink>
    </FooterLinkGroup>
  </div>
  <div class="border-t pt-5 flex items-center justify-between">
    <FooterCopyright href="/" by="Aquamark™" />
    <div>
      <FooterIcon href="https://www.linkedin.com/company/aquamark-integrated-services/">
        <Icon icon="mdi:linkedin" class="text-xl hover:text-blue-600 transition"/>
      </FooterIcon>
    </div>
  </div>
</Footer>

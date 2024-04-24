<template>
    <ProfileInfo 
        :photo="photo" 
        title="Jaison" 
        subtitle="@jaisonschmidt" 
        headline="Encontro 04 FIAP" 
    />

    <div class="max-w-xs mx-auto">
        <ButtonAction 
            link="https://www.linkedin.com/in/jaisonschmidt/" 
            title="LinkedIn" 
            icon="👔"
        />

        <ButtonAction 
            link="https://wa.me/+5554999776648" 
            title="Whatsapp" 
            icon="💬" 
        />

        <ButtonAction 
            link="https://github.com/jaisonschmidt" 
            title="Github" 
            icon="🛠" 
        />
    </div>
</template>

<script setup>
    import photo from '../assets/img/picture.jpg';
</script>
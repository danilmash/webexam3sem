<template lang="">
    <v-toolbar>
        <v-toolbar-title>
            <span class="text-h4">My</span>
            <span class="text-h3">Library</span>
        </v-toolbar-title>
        <v-btn class="bg-black text-white">
            <span>Выйти</span>
            <v-icon icon="mdi-exit-to-app" end></v-icon>
        </v-btn>
    </v-toolbar>

    <v-navigation-drawer>
        
            <v-container>
                <v-row>
                    <v-col class="d-flex justify-center" >
                        <v-avatar size="150" align-self="center">
                            <v-img src="../assets/ava.jpg" cover  ></v-img>
                        </v-avatar>
                    </v-col>
                </v-row>
                
                <v-list class="text-h5 mt-4">        
                    <v-list-item link >
                        <v-icon icon="mdi-home"></v-icon>
                        Главная
                    </v-list-item>     
                    <v-list-item link>
                        <v-icon icon="mdi-help-box"></v-icon>
                        Помощь
                    </v-list-item>   
                </v-list>
            </v-container>
    </v-navigation-drawer>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>
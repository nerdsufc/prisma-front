<template>
    <div class="grid h-screen place-items-center">
        <div class="flex flex-col p-2 items-center space-y-6 w-1/2 bg-base-100 shadow-xl form-control">
            <h3 class="login-title text-5xl p-2 font-bold text-primary">LOGIN</h3>
            <input class="input input-bordered input-sm w-full max-w-xs" type="text" placeholder="Usuário" />
            <input class="input input-bordered input-sm w-full max-w-xs" type="text" placeholder="Senha" />

            <div class="w-5/12 flex justify-start">
                <label class="label cursor-pointer">
                    <input type="checkbox" checked="checked" class="checkbox checkbox-primary" />
                    <span class="label-text mx-2">Lembre-me</span>
                </label>
            </div>
            <button class="btn btn-primary w-fit">Entrar</button>
            <div class="flex flex-col space-y-5">
                <div class="flex space-x-1">
                    <h3>Esqueceu sua senha?</h3>
                    <a href="#" class="text-center font-bold underline decoration-solid text-blue-500">Clique aqui.</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>

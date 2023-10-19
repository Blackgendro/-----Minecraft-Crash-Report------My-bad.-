# -----Minecraft-Crash-Report------My-bad.-
---- Minecraft Crash Report ----
// My bad.

Time: 2023-10-18 21:35:54
Description: Rendering entity in world

java.lang.IllegalArgumentException: Duplicate delegates
	at com.mojang.blaze3d.vertex.VertexMultiConsumer$Double.<init>(VertexMultiConsumer.java:44) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,xf:OptiFine:default}
	at com.mojang.blaze3d.vertex.VertexMultiConsumer.m_86168_(VertexMultiConsumer.java:20) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,xf:OptiFine:default}
	at com.github.alexthe666.alexsmobs.client.render.RenderCombJelly$RainbowLayer.render(RenderCombJelly.java:61) ~[alexsmobs-1.22.6.jar%23223!/:1.22.6] {re:classloading}
	at com.github.alexthe666.alexsmobs.client.render.RenderCombJelly$RainbowLayer.m_6494_(RenderCombJelly.java:54) ~[alexsmobs-1.22.6.jar%23223!/:1.22.6] {re:classloading}
	at net.minecraft.client.renderer.entity.LivingEntityRenderer.m_7392_(LivingEntityRenderer.java:215) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:betteranimationscollection.common.mixins.json:client.accessor.LivingEntityRendererAccessor,pl:mixin:APP:citadel.mixins.json:client.LivingEntityRendererMixin,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.LivingEntityRendererMixin,pl:mixin:A}
	at net.minecraft.client.renderer.entity.MobRenderer.m_7392_(MobRenderer.java:55) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,xf:OptiFine:default}
	at net.minecraft.client.renderer.entity.MobRenderer.m_7392_(MobRenderer.java:20) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,xf:OptiFine:default}
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_114384_(EntityRenderDispatcher.java:190) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:betteranimationscollection.common.mixins.json:client.accessor.EntityRenderDispatcherAccessor,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.EntityRenderDispatcherMixin,pl:mixin:A}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.lambda$renderEntityInInventory$0(EntityLinkButton.java:98) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.mojang.blaze3d.systems.RenderSystem.runAsFancy(RenderSystem.java:981) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.renderEntityInInventory(EntityLinkButton.java:97) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.m_87963_(EntityLinkButton.java:60) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at net.minecraft.client.gui.components.AbstractWidget.m_88315_(AbstractWidget.java:70) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_88315_(Screen.java:119) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.github.alexthe666.citadel.client.gui.GuiBasicBook.m_88315_(GuiBasicBook.java:285) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.github.alexthe666.alexsmobs.client.gui.GUIAnimalDictionary.m_88315_(GUIAnimalDictionary.java:33) ~[alexsmobs-1.22.6.jar%23223!/:1.22.6] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_280264_(Screen.java:109) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraftforge.client.ForgeHooksClient.drawScreenInternal(ForgeHooksClient.java:427) ~[forge-1.20.1-47.2.1-universal.jar%23291!/:?] {re:classloading}
	at net.minecraftforge.client.ForgeHooksClient.drawScreen(ForgeHooksClient.java:420) ~[forge-1.20.1-47.2.1-universal.jar%23291!/:?] {re:classloading}
	at jdk.internal.reflect.GeneratedMethodAccessor20.invoke(Unknown Source) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.optifine.reflect.Reflector.callVoid(Reflector.java:741) ~[preview_OptiFine_1.20.1_HD_U_I6_pre6.jar%23298!/:?] {re:classloading}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:1402) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1146) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.2.1.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at com.mojang.blaze3d.vertex.VertexMultiConsumer$Double.<init>(VertexMultiConsumer.java:44) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,xf:OptiFine:default}
	at com.mojang.blaze3d.vertex.VertexMultiConsumer.m_86168_(VertexMultiConsumer.java:20) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,xf:OptiFine:default}
	at com.github.alexthe666.alexsmobs.client.render.RenderCombJelly$RainbowLayer.render(RenderCombJelly.java:61) ~[alexsmobs-1.22.6.jar%23223!/:1.22.6] {re:classloading}
	at com.github.alexthe666.alexsmobs.client.render.RenderCombJelly$RainbowLayer.m_6494_(RenderCombJelly.java:54) ~[alexsmobs-1.22.6.jar%23223!/:1.22.6] {re:classloading}
	at net.minecraft.client.renderer.entity.LivingEntityRenderer.m_7392_(LivingEntityRenderer.java:215) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:betteranimationscollection.common.mixins.json:client.accessor.LivingEntityRendererAccessor,pl:mixin:APP:citadel.mixins.json:client.LivingEntityRendererMixin,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.LivingEntityRendererMixin,pl:mixin:A}
	at net.minecraft.client.renderer.entity.MobRenderer.m_7392_(MobRenderer.java:55) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,xf:OptiFine:default}
	at net.minecraft.client.renderer.entity.MobRenderer.m_7392_(MobRenderer.java:20) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,xf:OptiFine:default}
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_114384_(EntityRenderDispatcher.java:190) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:betteranimationscollection.common.mixins.json:client.accessor.EntityRenderDispatcherAccessor,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.EntityRenderDispatcherMixin,pl:mixin:A}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.lambda$renderEntityInInventory$0(EntityLinkButton.java:98) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.mojang.blaze3d.systems.RenderSystem.runAsFancy(RenderSystem.java:981) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.renderEntityInInventory(EntityLinkButton.java:97) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.m_87963_(EntityLinkButton.java:60) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at net.minecraft.client.gui.components.AbstractWidget.m_88315_(AbstractWidget.java:70) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_88315_(Screen.java:119) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.github.alexthe666.citadel.client.gui.GuiBasicBook.m_88315_(GuiBasicBook.java:285) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.github.alexthe666.alexsmobs.client.gui.GUIAnimalDictionary.m_88315_(GUIAnimalDictionary.java:33) ~[alexsmobs-1.22.6.jar%23223!/:1.22.6] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_280264_(Screen.java:109) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraftforge.client.ForgeHooksClient.drawScreenInternal(ForgeHooksClient.java:427) ~[forge-1.20.1-47.2.1-universal.jar%23291!/:?] {re:classloading}
	at net.minecraftforge.client.ForgeHooksClient.drawScreen(ForgeHooksClient.java:420) ~[forge-1.20.1-47.2.1-universal.jar%23291!/:?] {re:classloading}
	at jdk.internal.reflect.GeneratedMethodAccessor20.invoke(Unknown Source) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.optifine.reflect.Reflector.callVoid(Reflector.java:741) ~[preview_OptiFine_1.20.1_HD_U_I6_pre6.jar%23298!/:?] {re:classloading}
-- Entity being rendered --
Details:
	Entity Type: alexsmobs:comb_jelly (com.github.alexthe666.alexsmobs.entity.EntityCombJelly)
	Entity ID: 1568
	Entity Name: Comb Jelly
	Entity's Exact location: 0.00, 0.00, 0.00
	Entity's Block location: World: (0,0,0), Section: (at 0,0,0 in 0,0,0; chunk contains blocks 0,-64,0 to 15,319,15), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,-64,0 to 511,319,511)
	Entity's Momentum: 0.00, 0.00, 0.00
	Entity's Passengers: []
	Entity's Vehicle: null
Stacktrace:
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_114384_(EntityRenderDispatcher.java:190) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:betteranimationscollection.common.mixins.json:client.accessor.EntityRenderDispatcherAccessor,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.EntityRenderDispatcherMixin,pl:mixin:A}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.lambda$renderEntityInInventory$0(EntityLinkButton.java:98) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.mojang.blaze3d.systems.RenderSystem.runAsFancy(RenderSystem.java:981) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.renderEntityInInventory(EntityLinkButton.java:97) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.m_87963_(EntityLinkButton.java:60) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at net.minecraft.client.gui.components.AbstractWidget.m_88315_(AbstractWidget.java:70) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_88315_(Screen.java:119) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.github.alexthe666.citadel.client.gui.GuiBasicBook.m_88315_(GuiBasicBook.java:285) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.github.alexthe666.alexsmobs.client.gui.GUIAnimalDictionary.m_88315_(GUIAnimalDictionary.java:33) ~[alexsmobs-1.22.6.jar%23223!/:1.22.6] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_280264_(Screen.java:109) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraftforge.client.ForgeHooksClient.drawScreenInternal(ForgeHooksClient.java:427) ~[forge-1.20.1-47.2.1-universal.jar%23291!/:?] {re:classloading}
	at net.minecraftforge.client.ForgeHooksClient.drawScreen(ForgeHooksClient.java:420) ~[forge-1.20.1-47.2.1-universal.jar%23291!/:?] {re:classloading}
	at jdk.internal.reflect.GeneratedMethodAccessor20.invoke(Unknown Source) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.optifine.reflect.Reflector.callVoid(Reflector.java:741) ~[preview_OptiFine_1.20.1_HD_U_I6_pre6.jar%23298!/:?] {re:classloading}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:1402) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1146) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.2.1.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- Renderer details --
Details:
	Assigned renderer: com.github.alexthe666.alexsmobs.client.render.RenderCombJelly@4793a2a7
	Location: 0.00,0.00,0.00 - World: (0,0,0), Section: (at 0,0,0 in 0,0,0; chunk contains blocks 0,-64,0 to 15,319,15), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,-64,0 to 511,319,511)
	Rotation: 0.0
	Delta: 1.0
Stacktrace:
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_114384_(EntityRenderDispatcher.java:190) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:betteranimationscollection.common.mixins.json:client.accessor.EntityRenderDispatcherAccessor,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.EntityRenderDispatcherMixin,pl:mixin:A}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.lambda$renderEntityInInventory$0(EntityLinkButton.java:98) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.mojang.blaze3d.systems.RenderSystem.runAsFancy(RenderSystem.java:981) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.renderEntityInInventory(EntityLinkButton.java:97) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.github.alexthe666.citadel.client.gui.EntityLinkButton.m_87963_(EntityLinkButton.java:60) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at net.minecraft.client.gui.components.AbstractWidget.m_88315_(AbstractWidget.java:70) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_88315_(Screen.java:119) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at com.github.alexthe666.citadel.client.gui.GuiBasicBook.m_88315_(GuiBasicBook.java:285) ~[citadel-2.4.5-1.20.1.jar%23235!/:2.4.5-1.20.1] {re:classloading}
	at com.github.alexthe666.alexsmobs.client.gui.GUIAnimalDictionary.m_88315_(GUIAnimalDictionary.java:33) ~[alexsmobs-1.22.6.jar%23223!/:1.22.6] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.Screen.m_280264_(Screen.java:109) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:computing_frames,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:balm.mixins.json:ScreenAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraftforge.client.ForgeHooksClient.drawScreenInternal(ForgeHooksClient.java:427) ~[forge-1.20.1-47.2.1-universal.jar%23291!/:?] {re:classloading}
	at net.minecraftforge.client.ForgeHooksClient.drawScreen(ForgeHooksClient.java:420) ~[forge-1.20.1-47.2.1-universal.jar%23291!/:?] {re:classloading}
	at jdk.internal.reflect.GeneratedMethodAccessor20.invoke(Unknown Source) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.optifine.reflect.Reflector.callVoid(Reflector.java:741) ~[preview_OptiFine_1.20.1_HD_U_I6_pre6.jar%23298!/:?] {re:classloading}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:1402) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1146) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.2.1.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- Screen render details --
Details:
	Screen name: com.github.alexthe666.alexsmobs.client.gui.GUIAnimalDictionary
	Mouse location: Scaled: (398, 209). Absolute: (796.000000, 418.000000)
	Screen size: Scaled: (427, 240). Absolute: (854, 480). Scale factor of 2.000000
Stacktrace:
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:1402) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1146) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.2.1.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- Affected level --
Details:
	All players: 1 total; [LocalPlayer['BlackGendro'/70480, l='ClientLevel', x=59.38, y=64.25, z=513.79]]
	Chunk stats: 729, 453
	Level dimension: minecraft:overworld
	Level spawn location: World: (199,80,401), Section: (at 7,0,1 in 12,5,25; chunk contains blocks 192,-64,400 to 207,319,415), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,-64,0 to 511,319,511)
	Level time: 104263 game time, 29525 day time
	Server brand: forge
	Server type: Non-integrated multiplayer server
Stacktrace:
	at net.minecraft.client.multiplayer.ClientLevel.m_6026_(ClientLevel.java:590) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,xf:OptiFine:default,xf:fml:xaeroworldmap:xaero_wm_clientworldclass,xf:fml:xaerominimap:xaero_clientworldclass,re:classloading,xf:OptiFine:default,xf:fml:xaeroworldmap:xaero_wm_clientworldclass,xf:fml:xaerominimap:xaero_clientworldclass,pl:mixin:APP:citadel.mixins.json:client.ClientLevelMixin,pl:mixin:APP:architectury.mixins.json:MixinClientLevel,pl:mixin:A}
	at net.minecraft.client.Minecraft.m_91354_(Minecraft.java:2319) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:735) ~[client-1.20.1-20230612.114412-srg.jar%23286!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:mixins.ipnext.json:MixinMinecraftClient,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:itemphysic.mixins.json:MinecraftMixin,pl:mixin:APP:playerrevive.mixins.json:MinecraftAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.2.1.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.1.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- Last reload --
Details:
	Reload number: 1
	Reload reason: initial
	Finished: Yes
	Packs: vanilla, mod_resources, file/Shiny+Trims+v5+(Optifine).zip

-- System Details --
Details:
	Minecraft Version: 1.20.1
	Minecraft Version ID: 1.20.1
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.8, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 837328168 bytes (798 MiB) / 1979711488 bytes (1888 MiB) up to 2147483648 bytes (2048 MiB)
	CPUs: 6
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Core(TM) i5-9400F CPU @ 2.90GHz
	Identifier: Intel64 Family 6 Model 158 Stepping 10
	Microarchitecture: Coffee Lake
	Frequency (GHz): 2.90
	Number of physical packages: 1
	Number of physical CPUs: 6
	Number of logical CPUs: 6
	Graphics card #0 name: NVIDIA GeForce GTX 1660
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x2184
	Graphics card #0 versionInfo: DriverVersion=31.0.15.3168
	Memory slot #0 capacity (MB): 8192.00
	Memory slot #0 clockSpeed (GHz): 2.67
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 8192.00
	Memory slot #1 clockSpeed (GHz): 2.67
	Memory slot #1 type: DDR4
	Virtual memory max (MB): 23992.55
	Virtual memory used (MB): 16206.63
	Swap memory total (MB): 7680.00
	Swap memory used (MB): 152.34
	JVM Flags: 9 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	Launched Version: 1.20.1-forge-47.2.1
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: NVIDIA GeForce GTX 1660/PCIe/SSE2 GL version 4.6.0 NVIDIA 531.68, NVIDIA Corporation
	Window size: 854x480
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: id=1282, source=API, type=ERROR, severity=HIGH, message='GL_INVALID_OPERATION error generated. Texture name does not refer to a texture object generated by OpenGL.' x 1
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'
	Type: Client (map_client.txt)
	Graphics mode: fast
	Resource Packs: vanilla, mod_resources, file/Shiny+Trims+v5+(Optifine).zip
	Current Language: es_mx
	CPU: 6x Intel(R) Core(TM) i5-9400F CPU @ 2.90GHz
	OptiFine Version: OptiFine_1.20.1_HD_U_I6_pre6
	OptiFine Build: 20230727-130058
	Render Distance Chunks: 20
	Mipmaps: 4
	Anisotropic Filtering: 1
	Antialiasing: 0
	Multitexture: false
	Shaders: ComplementaryUnbound_r5.0.zip
	OpenGlVersion: 4.6.0 NVIDIA 531.68
	OpenGlRenderer: NVIDIA GeForce GTX 1660/PCIe/SSE2
	OpenGlVendor: NVIDIA Corporation
	CpuCount: 6
	ModLauncher: 10.0.9+10.0.9+main.dcd20f30
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		eventbus-6.0.5.jar eventbus PLUGINSERVICE 
		fmlloader-1.20.1-47.2.1.jar slf4jfixer PLUGINSERVICE 
		fmlloader-1.20.1-47.2.1.jar object_holder_definalize PLUGINSERVICE 
		fmlloader-1.20.1-47.2.1.jar runtime_enum_extender PLUGINSERVICE 
		fmlloader-1.20.1-47.2.1.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		fmlloader-1.20.1-47.2.1.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.9.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar OptiFine TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		javafml@null
		kotlinforforge@4.5.0
		lowcodefml@null
	Mod List: 
		BetterAnimationsCollection-v8.0.0-1.20.1-Forge.jar|Better Animations Collection  |betteranimationscollection    |8.0.0               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		trashslot-forge-1.20-15.1.0.jar                   |TrashSlot                     |trashslot                     |15.1.0              |DONE      |Manifest: NOSIGNATURE
		endertrigon-1.20.1-1.0.jar                        |Ender Trigon                  |endertrigon                   |1.0                 |DONE      |Manifest: NOSIGNATURE
		player-animation-lib-forge-1.0.2-rc1+1.20.jar     |Player Animator               |playeranimator                |1.0.2-rc1+1.20      |DONE      |Manifest: NOSIGNATURE
		jei-1.20.1-forge-15.2.0.27.jar                    |Just Enough Items             |jei                           |15.2.0.27           |DONE      |Manifest: NOSIGNATURE
		VisualWorkbench-v8.0.0-1.20.1-Forge.jar           |Visual Workbench              |visualworkbench               |8.0.0               |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		libraryferret-forge-1.20.1-4.0.0.jar              |Library ferret                |libraryferret                 |4.0.0               |DONE      |Manifest: NOSIGNATURE
		sophisticatedcore-1.20.1-0.5.89.425.jar           |Sophisticated Core            |sophisticatedcore             |0.5.89.425          |DONE      |Manifest: NOSIGNATURE
		MonsterPlus-Forge1.20.1-v1.1.6.1.jar              |Monster Plus                  |monsterplus                   |1.0                 |DONE      |Manifest: NOSIGNATURE
		villagernames-1.20.1-5.2.jar                      |Villager Names                |villagernames                 |5.2                 |DONE      |Manifest: NOSIGNATURE
		XaerosWorldMap_1.34.1_Forge_1.20.jar              |Xaero's World Map             |xaeroworldmap                 |1.34.1              |DONE      |Manifest: NOSIGNATURE
		EnhancedVisuals_FORGE_v1.6.9_mc1.20.1.jar         |EnhancedVisuals               |enhancedvisuals               |1.6.9               |DONE      |Manifest: NOSIGNATURE
		citadel-2.4.5-1.20.1.jar                          |Citadel                       |citadel                       |2.4.5               |DONE      |Manifest: NOSIGNATURE
		alexsmobs-1.22.6.jar                              |Alex's Mobs                   |alexsmobs                     |1.22.6              |DONE      |Manifest: NOSIGNATURE
		Dungeon+Crawl-1.20.1-2.3.14.jar                   |Dungeon Crawl                 |dungeoncrawl                  |2.3.14              |DONE      |Manifest: NOSIGNATURE
		sophisticatedbackpacks-1.20.1-3.18.59.909.jar     |Sophisticated Backpacks       |sophisticatedbackpacks        |3.18.59.909         |DONE      |Manifest: NOSIGNATURE
		u_team_core-forge-1.20.1-5.1.4.269.jar            |U Team Core                   |uteamcore                     |5.1.4.269           |DONE      |Manifest: f4:a6:0b:ee:cb:8a:1a:ea:9f:9d:45:91:8f:8b:b3:ae:26:f3:bf:05:86:1d:90:9e:f6:32:2a:1a:ed:1d:ce:b0
		bygonenether-1.3.2-1.20.x.jar                     |Bygone Nether                 |bygonenether                  |1.3.2               |DONE      |Manifest: NOSIGNATURE
		balm-forge-1.20.1-7.1.4.jar                       |Balm                          |balm                          |7.1.4               |DONE      |Manifest: NOSIGNATURE
		cloth-config-11.1.106-forge.jar                   |Cloth Config v10 API          |cloth_config                  |11.1.106            |DONE      |Manifest: NOSIGNATURE
		ctov-3.3.4.jar                                    |ChoiceTheorem's Overhauled Vil|ctov                          |3.3.4               |DONE      |Manifest: NOSIGNATURE
		castle_dungeons-4.0.0-1.20-forge.jar              |Castle Dungeons               |castle_dungeons               |4.0.0               |DONE      |Manifest: NOSIGNATURE
		emotecraft-for-MC1.20.1-2.2.7-b.build.50-forge.jar|Emotecraft                    |emotecraft                    |2.2.7-b.build.50    |DONE      |Manifest: NOSIGNATURE
		DungeonsArise-1.20.1-2.1.57-release.jar           |When Dungeons Arise           |dungeons_arise                |2.1.57-1.20.1       |DONE      |Manifest: NOSIGNATURE
		client-1.20.1-20230612.114412-srg.jar             |Minecraft                     |minecraft                     |1.20.1              |DONE      |Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		voicechat-forge-1.20.1-2.4.26.jar                 |Simple Voice Chat             |voicechat                     |1.20.1-2.4.26       |DONE      |Manifest: NOSIGNATURE
		soundphysics-forge-1.20.1-1.2.1.jar               |Sound Physics Remastered      |sound_physics_remastered      |1.20.1-1.2.1        |DONE      |Manifest: NOSIGNATURE
		libIPN-forge-1.20-4.0.0.jar                       |libIPN                        |libipn                        |4.0.0               |DONE      |Manifest: NOSIGNATURE
		TerraBlender-forge-1.20.1-3.0.0.169.jar           |TerraBlender                  |terrablender                  |3.0.0.169           |DONE      |Manifest: NOSIGNATURE
		mysticsbiomes-1.20.1-3.1.2.jar                    |Mystic's Biomes               |mysticsbiomes                 |1.20.1-3.2.0        |DONE      |Manifest: NOSIGNATURE
		bettercombat-forge-1.7.4+1.20.1.jar               |Better Combat                 |bettercombat                  |1.7.4+1.20.1        |DONE      |Manifest: NOSIGNATURE
		MoreBows-1.0.13+1.20.x.forge.jar                  |More Bows Restrung            |morebows                      |1.0.13              |DONE      |Manifest: NOSIGNATURE
		silent-lib-1.20.1-8.0.0.jar                       |Silent Lib                    |silentlib                     |8.0.0               |DONE      |Manifest: NOSIGNATURE
		BiomesOPlenty-1.20.1-18.0.0.598.jar               |Biomes O' Plenty              |biomesoplenty                 |18.0.0.598          |DONE      |Manifest: NOSIGNATURE
		Jade-1.20.1-forge-11.6.1.jar                      |Jade                          |jade                          |11.6.1              |DONE      |Manifest: NOSIGNATURE
		explorify-v1.3.0-mc1.20u1.20.1.jar                |Explorify                     |explorify                     |1.3.0-mc1.20u1.20.1 |DONE      |Manifest: NOSIGNATURE
		CreativeCore_FORGE_v2.11.5_mc1.20.1.jar           |CreativeCore                  |creativecore                  |2.11.5              |DONE      |Manifest: NOSIGNATURE
		CookingwithMindthemoodsV9.jar                     |Cooking with Mindthemoods     |cooking_with_mindthemoods     |1.0.0               |DONE      |Manifest: NOSIGNATURE
		kffmod-4.5.0.jar                                  |Kotlin For Forge              |kotlinforforge                |4.5.0               |DONE      |Manifest: NOSIGNATURE
		cluttered-2.1-1.20.1.jar                          |Cluttered                     |luphieclutteredmod            |2.1                 |DONE      |Manifest: NOSIGNATURE
		L_Enders_Cataclysm-1.39+-1.20.1.jar               |Cataclysm Mod                 |cataclysm                     |1.0                 |DONE      |Manifest: NOSIGNATURE
		curios-forge-5.3.5+1.20.1.jar                     |Curios API                    |curios                        |5.3.5+1.20.1        |DONE      |Manifest: NOSIGNATURE
		Xaeros_Minimap_23.8.2_Forge_1.20.jar              |Xaero's Minimap               |xaerominimap                  |23.8.2              |DONE      |Manifest: NOSIGNATURE
		right-click-harvest-3.2.0+1.20.1-forge.jar        |Right Click Harvest           |rightclickharvest             |3.2.0+1.20.1-forge  |DONE      |Manifest: NOSIGNATURE
		hmag-forge-mc1.20.1-9.0.2.jar                     |Hostile Mobs and Girls        |hmag                          |9.0.2               |DONE      |Manifest: NOSIGNATURE
		gravestone-1.20.1-1.0.5.jar                       |Gravestone Mod                |gravestone                    |1.20.1-1.0.5        |DONE      |Manifest: NOSIGNATURE
		collective-1.20.1-6.66.jar                        |Collective                    |collective                    |6.66                |DONE      |Manifest: NOSIGNATURE
		advancednetherite-forge-2.0.2-1.20.1.jar          |Advanced Netherite            |advancednetherite             |2.0.2               |DONE      |Manifest: NOSIGNATURE
		bettervillage-forge-1.20.1-3.2.0.jar              |Better village                |bettervillage                 |3.1.0               |DONE      |Manifest: NOSIGNATURE
		invhud.forge.1.20.1-3.4.18.jar                    |Inventory HUD+(Forge edition) |inventoryhud                  |3.4.18              |DONE      |Manifest: NOSIGNATURE
		InventoryProfilesNext-forge-1.20-1.10.7.jar       |Inventory Profiles Next       |inventoryprofilesnext         |1.10.7              |DONE      |Manifest: NOSIGNATURE
		architectury-9.1.12-forge.jar                     |Architectury                  |architectury                  |9.1.12              |DONE      |Manifest: NOSIGNATURE
		justhammers-forge-2.0.0+mc1.20.1.jar              |Just Hammers                  |justhammers                   |2.0.0+mc1.20.1      |DONE      |Manifest: NOSIGNATURE
		spore_1.20.1_2.0.0b.jar                           |Spore                         |spore                         |2.0.0               |DONE      |Manifest: NOSIGNATURE
		lootr-1.20-0.7.30.73.jar                          |Lootr                         |lootr                         |0.7.29.68           |DONE      |Manifest: NOSIGNATURE
		Mvw-2.0.1.jar                                     |MoreVanillaWeapons            |mvw                           |2.0.1               |DONE      |Manifest: NOSIGNATURE
		ItemPhysic_FORGE_v1.6.14_mc1.20.1.jar             |ItemPhysic                    |itemphysic                    |1.6.14              |DONE      |Manifest: NOSIGNATURE
		PuzzlesLib-v8.0.23-1.20.1-Forge.jar               |Puzzles Lib                   |puzzleslib                    |8.0.23              |DONE      |Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		BetterF3-7.0.1-Forge-1.20.1.jar                   |BetterF3                      |betterf3                      |7.0.1               |DONE      |Manifest: NOSIGNATURE
		FallingTree-1.20.1-5.0.0b1.jar                    |FallingTree                   |fallingtree                   |5.0.0b1             |DONE      |Manifest: 3c:8e:df:6c:df:a6:2a:9f:af:64:ea:04:9a:cf:65:92:3b:54:93:0e:96:50:b4:52:e1:13:42:18:2b:ae:40:29
		BNBloodParticlesMod+1.20.1+v0.7.9.jar             |BN Blood Particles Mod        |bn_blood_particles_mod        |0.7.9               |DONE      |Manifest: NOSIGNATURE
		ScalingHealth-1.20.1-8.0.1+8.jar                  |Scaling Health                |scalinghealth                 |8.0.1+8             |DONE      |Manifest: NOSIGNATURE
		forge-1.20.1-47.2.1-universal.jar                 |Forge                         |forge                         |47.2.1              |DONE      |Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
		appleskin-forge-mc1.20.1-2.5.1.jar                |AppleSkin                     |appleskin                     |2.5.1+mc1.20.1      |DONE      |Manifest: NOSIGNATURE
		PlayerRevive_FORGE_v2.0.19_mc1.20.1.jar           |PlayerRevive                  |playerrevive                  |2.0.19              |DONE      |Manifest: NOSIGNATURE
		xptome-1.20.1-2.1.8.jar                           |XP Tome                       |xpbook                        |2.1.8               |DONE      |Manifest: NOSIGNATURE
	Crash Report UUID: 793a7ed6-d2b6-4bb9-8ec5-a685d84f1e94
	FML: 47.2
	Forge: net.minecraftforge:47.2.1

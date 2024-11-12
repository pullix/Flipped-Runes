<script>
    import { T } from "@threlte/core";
    import CharacterController from "./CharacterController.svelte";
</script>

<T.Mesh>
    <T.BoxGeometry />
    <T.MeshStandardMaterial color="hotpink" />
</T.Mesh>

<CharacterController />
<T.DirectionalLight position={[10, 10, 10]} />
<script>
    import { T } from "@threlte/core";
  import { BoxGeometry, DirectionalLight } from "three";
</script>

<T.Mesh>
    <T.BoxGeometry />
    <T.MeshStandardMaterial color="hotpink" />
</T.Mesh>
<T.DirectionalLight position={[10, 10, 10]} />
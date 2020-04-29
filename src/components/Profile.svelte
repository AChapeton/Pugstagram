<script>
  export let nickname;
  export let name;
</script>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img src="https://scontent-mia3-2.cdninstagram.com/v/t51.2885-19/s320x320/54513051_426450698187294_4005819244250923008_n.jpg?_nc_ht=scontent-mia3-2.cdninstagram.com&_nc_ohc=k2bSoDY5TKEAX84X4Ld&oh=fcfbf16a14b0d9b9978f4ed9f41af0d6&oe=5ED261EE" alt="Profile picture">
        </div>
        <div class="Profile-info">
            <h2>{nickname}</h2>
            <span>{name}</span>
        </div>
    </div>
</div>
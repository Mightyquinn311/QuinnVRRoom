 using UnityEngine;

/// <summary>
/// Destroys object after a few seconds
/// </summary>
public class HatTextDestroy : MonoBehaviour
{
    private void Start()
    {
        Destroy(gameObject);
    }
}

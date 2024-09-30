# To-find-compressive-strength-of-brick-using-python
To find compressive strength of brick using python
def compressive_strength(max_load, length, width):
    """
    Calculate the compressive strength of a brick.
    
    Parameters:
    max_load (float): The maximum load at which the brick fails (in Newtons).
    length (float): The length of the brick (in mm).
    width (float): The width of the brick (in mm).
    
    Returns:
    float: Compressive strength of the brick (in N/mm²).
    """
    area = length * width  # Area in mm²
    compressive_strength = max_load / area  # Strength in N/mm²
    return compressive_strength


strength = compressive_strength(max_load, length, width)
print(f"Compressive Strength of the Brick: {strength:.2f} N/mm²")

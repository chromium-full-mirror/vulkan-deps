# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b888ebcee8ffaa59536b5f33277936536249d9be',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '256ef38472091f70937c8df27fe68ea340a1cd0b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '7168a5ad041f6b6b9170f027c7417f98a2056ff0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '2e743e96b990f7390290630243b00ca0a75b8547',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b11eecd68fb4b770f30fe2c9da522ff966f95b1e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'bf4aec7ddb0f46d729ebd3255296d9fe8eed73ec',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e4fb76dc08f139df0436e9c3031f75be5e1f6264',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '03e1445cc7cce22baeeef8eff7bb934362d040eb',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4a5a8580822959258e20491c459ae4cc2b7270b4',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}

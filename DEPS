# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '968eb87c07f957520b7a96433933bb8d2bb0fc3c',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'b89039fa06c46c8b80aff35035f27d821fd11c5c',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '04f10f650d514df88b76d25e83db360142c7b174',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a66a95eecf5102f2b19d6208385538c7c29aa7a1',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3cfca3829608e778cf59b0dab55d77f4f6c79bee',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '075488ccd6600fea664e10ee2f946c76086827d2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '362c28b8e13292f0fca1b0c9ce3ba515fe9b71a1',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '906b27a77f4857fae6da3062df4cf6ab0c06e8d4',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'baf8e33b54b9e0cd2317f74664dcba3ea2d028d2',
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
